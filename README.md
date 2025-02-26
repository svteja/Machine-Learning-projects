This Repository contains multiple Machine Learning with different Models. Scroll down to read the projects overview. Click on a project title to explore its files.
![Screenshot 2025-02-26 120121](https://github.com/user-attachments/assets/a1434a0c-8117-4c9e-a699-13a651e456d0)


📂 Notebooks/ –
Contains Jupyter notebooks for data exploration, model training, and evaluation (new_cred.ipynb).

📂 Datasets/ –
Includes the dataset used for training and testing the models.

📂 Models/ –
Serialized machine learning models (e.g., .pkl files) for easy deployment.

📂 Images/ –
Visuals of key data insights and model performance metrics.


## 📊 Projects
### 1.[American Express credit card Risk prediction](creditriskprediction/) 

## 📌 Project Overview

### Credit Risk Prediction

This  contains a machine learning project focused on predicting credit risk using various customer and financial data points. The model aims to assess the likelihood of Credit default, helping financial institutions make data-driven lending decisions. It includes Jupyter notebooks with end-to-end workflows, from data preprocessing to model evaluation. The project is deployed in the local system.


📊 Models & Techniques

Logistic Regression –
A baseline model to classify credit risk (low/high).

Random Forest Classifier –
Ensemble method for improved prediction accuracy and handling imbalanced data.

XGBoost –
Gradient boosting algorithm for optimized credit risk predictions.

SMOTE –
Applied to handle class imbalance by oversampling minority classes.

Hyperparameter Tuning –
Grid Search & Randomized Search for model optimization.

🚀 Key Features

🔍 Credit Risk Analysis

Predicts the probability of default based on customer profiles, transaction history, and credit scores.

📊 Feature Importance
Highlights which factors (e.g., income, debt-to-income ratio, credit history) most influence risk prediction.

📈 Model Performance Metrics
Evaluates models using metrics like Accuracy, Precision, Recall, F1-Score, and ROC-AUC for reliable results.

💡 Data Visualizations
Interactive plots showcasing distribution of risk levels, correlation heatmaps, and ROC curves for model evaluation.
## 


### 2.[Loan Approval prediction](LoanApprovalPrediction/) 

## 📌 Project Overview

### Loan approval prediction
This project focuses on predicting loan approval status based on customer financial and demographic data. The model helps banks and financial institutions make data-driven decisions by assessing applicants' eligibility for loans. The project includes end-to-end workflows, from data preprocessing to model evaluation, and is deployed as a Flask web application for real-time predictions.

📊 Models & Techniques

 Logistic Regression – Baseline classification model for loan approval prediction.

 Random Forest Classifier – An ensemble method improving accuracy and handling missing data.

 Desicion Tree – A technique for better decision-making.

 Hyperparameter Tuning – Grid Search & Randomized Search to optimize model performance.

🔍 Loan Eligibility Prediction

Determines whether an applicant qualifies for a loan based on income, credit history, and other financial factors.

Provides a clear decision: Loan Approved ✅ or Loan Not Approved ❌

📊 Feature Importance Analysis
Identifies key factors influencing loan approvals, such as income, loan amount, credit history, and employment status.

📈 Model Performance Metrics
Evaluates models using Accuracy, Precision, Recall, F1-Score to ensure reliability.

📊 Data Visualizations
Interactive charts showing approval rates, applicant income distributions, loan amount trends, and credit score impacts.
## 
### 3.[Credit Scoring & Customer Segmentation](CreditScoringSegmentation/)
## 📌 Project Overview

This project applies K-Means clustering to segment customers based on their credit scores. It helps financial institutions categorize customers into different risk groups for better decision-making, loan approvals, and personalized financial products. The project includes data preprocessing, clustering analysis, and interactive visualizations for insights.

📊 Techniques & Methodology

K-Means Clustering – Used to segment customers into 4 distinct credit score groups.

Feature Selection – Clustering is based on customers' Credit Scores.

Elbow Method – Helps determine the optimal number of clusters.

🔍 Customer Segmentation Based on Credit Score

Groups customers into 4 clusters representing different credit worthiness levels (Very Low, Low, Good, Excellent).

Helps banks target high-risk and low-risk customers effectively.

📊 Cluster Analysis & Insights

Identifies patterns in customer credit behavior.

Helps in risk assessment and customized financial offerings.

📈 Data Visualizations

Cluster distribution charts to visualize credit score segmentation.

Interactive scatter plots showing how customers are grouped.

