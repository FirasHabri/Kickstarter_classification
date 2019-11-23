# Kickstarter_classification
create a machine learning model to predict, if a kickstarter project is going to be successful or not based on chosen features.

## Overview : 
This notebook is to find out, if there are any features, which influence the Kickstarter project to succeed or fail. That is why we are going to focus only data which has state 'successful' or 'failed'.

## Content:
 * Loading Modules
 * Loading the data set you can see it at "https://www.kaggle.com/kemical/kickstarter-projects"
 * Data exploration
 * Data preparation
 * Model Selection
 * Principal Component Analysis (PCA) "used for  feature selection and dimensionality reduction"
 * Model evaluation
 
## Results:
| Model  | Score |
| ------------- | ------------- |
| Multilayer Perceptron  | 68.6  |
| KNN  | 67.7  |
| GradientBoostingClassifier  | 67.3  |
| BaggingClassifier  | 66.4  |
| Logistic Regression  | 64.3  |
| Bagging PCA  | 64.3  |
| AdaBoostClassifier  | 63.7  |
| Linear Support Vector Machine  | 63.3  |
| Random Forest  | 62.4  |
| Radial Kernel SVMDecision Tree  | 60.8  |
| Radial Kernel SVM with PCA  | 52.9  |
| Linear Support Vector Machine with PCA  | 52.4  |
