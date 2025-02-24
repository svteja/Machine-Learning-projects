Project Overview
Developed a machine learning model to predict the credit risk of loan applicants based on features like credit score, income, employment history, delinquency history, and more.
Engineered features from customer data to evaluate risk factors, including debt-to-income ratio, education level, and customer satisfaction scores.
How will this project help?
This project assists financial institutions in evaluating loan applicants more accurately, reducing default risks and enhancing credit approval decisions.
Resources Used
Packages: pandas, numpy, sklearn, matplotlib, seaborn, xgboost, imbalanced-learn
Dataset: credit_card_data.csv
Exploratory Data Analysis (EDA) and Data Cleaning
Removed unwanted columns: 'Unnamed: 14', 'Unnamed: 15', 'Unnamed: 16'
Handled missing values:
Filled NaN values in 'Cust_Satisfaction_Score' based on delinquency history and income
Updated 'Education_Level' for unknown entries based on job titles
Categorical Data Cleaning:
Standardized gender labels ('M' → 'Male', 'F' → 'Female')
Handled inconsistent job titles and education levels
Analyzed distributions: Used bar plots, count plots, and correlation matrices to understand feature relationships
Feature Engineering
Created new features:
Customer Satisfaction Score based on delinquency and income
Adjusted education levels using job titles to fill 'Unknown' entries
Categorical encoding: Applied Label Encoding and One-Hot Encoding where necessary
Balanced dataset: Used SMOTE (Synthetic Minority Over-sampling Technique) to handle class imbalance
Feature Scaling: Applied StandardScaler to standardize numerical features
Model Building and Evaluation
Metrics: Accuracy, Precision, Recall, F1-Score, AUC-ROC

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
XGBoost Classifier
Evaluation:
Used ROC curves, confusion matrices, and classification reports
Applied GridSearchCV for hyperparameter tuning
Model Prediction
The final model predicts the likelihood of default for new applicants
Provides a risk score to help lenders make informed decisions
