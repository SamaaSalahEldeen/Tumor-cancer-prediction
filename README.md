overview
This repository contains Python code for predicting cancer tumors using machine learning models.
Libraries Used
NumPy
Pandas
Matplotlib
Seaborn
TensorFlow
Data Preprocessing
The data is loaded and checked for missing values.
Columns with missing values are dropped.
Categorical data (diagnosis) is encoded using LabelEncoder.
A pair plot and correlation matrix are generated to visualize relationships between variables.

Machine Learning Models
Three machine learning models are implemented and trained on the dataset:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier

Ensemble Model
A Voting Classifier is implemented using Logistic Regression, Decision Tree, and Random Forest models. The ensemble model's training and testing scores are evaluated, and a confusion matrix is presented.
