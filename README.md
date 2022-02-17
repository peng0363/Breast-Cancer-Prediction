# Breast-Cancer-Prediction

I built the predictive models to predict the diagnosis with 4 methods, decision tree, logistic regression, k-nearest neighbors and support vector machine. I measured the model goodness by accuracy, which is among all predictions, the percentage of correct predictions.

To decide the best model, I conducted nested grid search CV on the four models. By comparing the accuracy among the four models, decision tree (0.9244), KNN (0.9366), logistic regression (0.9402) and SVM (0.9384), I found out the best model is logistic regression. I then conducted hyperparameter tuning on the logistic regression model, the final accuracy on testing data is 0.9736. In addition, I plotted the ROC curve and lift curve to gain more insights. 


The original data source is from Kaggle. Link as below:  
https://www.kaggle.com/uciml/breast-cancer-wisconsin-data/code?datasetId=180&sortBy=voteCount
