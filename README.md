# Create-an-AI-ML-classification-model-with-a-simple-GUI
This model is a classification model. Using flower dataset from Kaggle composed of more than 4000 images 
I trained this model using AlexNet,and evaluated the model using Cross validation method.
The reason I chose cross validation because it gives more accurate results, and that it because it alows you to use the whole dataset to train 
the model.

You have to chose the number of folds to devide your dataset then start training.
This article had explained Cross validation method in details, you can have a look.
https://www.analyticsvidhya.com/blog/2021/09/how-to-apply-k-fold-averaging-on-deep-learning-classifier/#:~:text=conventional%20holdout%20method.-,What%20is%20K%2DFold%3F,used%20for%20the%20training%20purpose.

After training the model, to calculate the model accuracy you have to take the average of each fold accuracy. Then you can create your simple GUI.
I used Tkinter library but there are multible GUI libraries to create your GUI.

It's immportant to mention that my model accuracy is over fitting, you may have different results according to your dataset and
other hyper-parameters that contros the model accuracy.
