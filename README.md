Assignment 6 - Breast Cancer Classification
The purpose of this assignment is to apply machine learning classification techniques using Python and the Scikit-Learn module on real-world data. The project aims to classify breast cancer cases as benign or malignant using machine learning, focusing on different models, including tree-based classifiers.

The project workflow involved the following steps:
Data Preparation: Imported the necessary libraries and loaded the breast cancer dataset from Scikit-Learn. The data was split into 80% for training and 20% for testing.
Model Selection: Used three different machine learning models to train and test performance:
logistic regression
Random Forest Classifier
Support Vector Classifier (SVC)
Cross-Validation: Applied Stratified K-Fold cross-validation to ensure consistent class distribution across the folds. The dataset was split into 5 folds, and the cross_val_score method was used to evaluate the model's performance on each fold.
Evaluation: Compared models based on their accuracy scores across all folds and their overall average accuracy. One model performed better than the others, and this was determined using metrics from cross-validation.
Parameters: The parameter n_splits=5 was set for the Stratified K-Fold. The process involved fitting the models, predicting outcomes, and calculating performance metrics.

Chatgpt guidance 
https://chatgpt.com/c/6711c653-1af0-800a-8507-9fa177cd946b
