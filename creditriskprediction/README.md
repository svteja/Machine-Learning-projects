## 📌 Project Overview
1) Developed a machine learning model to predict the credit risk of loan applicants based on features like Gender, income, employment history, delinquency 
 history, and more.
2) Engineered features from customer data to evaluate risk factors, including Credit_Limit, education level, and customer satisfaction scores.

## How will this project help?
   This project assists financial institutions in evaluating loan applicants more accurately, reducing default risks and enhancing credit approval decisions.
## Resources Used
Packages: pandas, numpy, sklearn, matplotlib, seaborn, xgboost, imbalanced-learn etc.

Dataset: credit_card_data.csv

## Exploratory Data Analysis (EDA) and Data Cleaning
Removed unwanted columns: 'Unnamed: 14', 'Unnamed: 15', 'Unnamed: 16'
#### Handled missing values:
1)Filled NaN values in 'Cust_Satisfaction_Score' based on delinquency history and income

2)Updated 'Education_Level' for unknown entries based on job titles
#### Categorical Data Cleaning:
1)Standardized gender labels ('M' → 'Male', 'F' → 'Female')

2)Handled inconsistent job titles and education levels

3)Removing duplicated rows.
## EDA:
Analyzed distributions: Used bar plots, count plots, and correlation matrices to understand feature relationships
![Screenshot 2025-02-24 112450](https://github.com/user-attachments/assets/25c22bb8-c935-4926-91cf-16b78d2e5faa)
![Screenshot 2025-02-24 112519](https://github.com/user-attachments/assets/3447d215-e310-41c0-89b7-61eff63262d0)
![Screenshot 2025-02-24 112623](https://github.com/user-attachments/assets/117cc75e-dc80-4d00-b4d6-5ac264c4bdd6)



## Feature Engineering
Customer Satisfaction Score based on delinquency and income

Adjusted education levels using job titles to fill 'Unknown' entries

Categorical encoding: Applied Label Encoding and One-Hot Encoding where necessary

Balanced dataset: Used SMOTE (Synthetic Minority Over-sampling Technique) to handle class imbalance
![Screenshot 2025-02-24 112425](https://github.com/user-attachments/assets/aee6747b-e356-4bdb-bfba-9f1f2755bd36)


Feature Scaling: Applied StandardScaler to standardize numerical features
## Pipeline
Used pipeline to create  flow of one-hot encoding,standard scaler,smote and random forest
![Screenshot 2025-02-24 113009](https://github.com/user-attachments/assets/a9b605f9-7c22-4831-9dda-ef21e7be2340)


## Deployment
Model is deployed in the local server using pickle file and flask
![deploy](https://github.com/user-attachments/assets/43081447-969c-4a0b-be02-88dadbaef1cb)

## Machine Learning Algorithms used
1)Logistic Regression

2)Decision Tree Classifier

3)Random Forest Classifier

4)XGBoost Classifier
## Evaluation:
Used ROC curves, confusion matrices, and classification reports

Metrics: Accuracy, Precision, Recall, F1-Score, AUC-ROC

Applied GridSearchCV for hyperparameter tuning

![Screenshot 2025-02-24 114201](https://github.com/user-attachments/assets/b2db5bb8-06b3-48fc-a59f-60b159f202bd)

## Model Prediction
The final model predicts the likelihood of default for new applicants
Provides a High Credit Risk or Low Credit Risk to help lenders make informed decisions


![Screenshot 2025-02-24 113826](https://github.com/user-attachments/assets/fb21a938-fb04-444a-a31f-4aec30e3207c)

