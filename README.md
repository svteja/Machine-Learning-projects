This Repository contains multiple Machine Learning with different Models. Scroll down to read the projects Details. Click on a project title to explore its files and project flow.

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
### Credit Risk Prediction

This  contains a machine learning project focused on predicting credit risk using various customer and financial data points. The model aims to assess the likelihood of Credit default, helping financial institutions make data-driven lending decisions. It includes Jupyter notebooks with end-to-end workflows, from data preprocessing to model evaluation. The project is deployed in the local system.

## 📌 Project Details
### Problem Statement:
Financial institutions need to assess the risk associated with granting credit to customers. The goal is to predict whether a customer is at risk of default based on historical transaction data and demographic details.

### 🔹Solution:

Used Random Forest Classifier with hyperparameter tuning to optimize model performance.

Addressed class imbalance using SMOTE.

Evaluated using Accuracy, Precision, Recall, and AUC Score.

Deployed using Flask, allowing users to input customer details and get a risk prediction.


## 

### 2.[Loan Approval prediction](LoanApprovalPrediction/) 

## 📌 Project Details

### Loan approval prediction
This project focuses on predicting loan approval status based on customer financial and demographic data. The model helps banks and financial institutions make data-driven decisions by assessing applicants' eligibility for loans. The project includes end-to-end workflows, from data preprocessing to model evaluation, and is deployed as a Flask web application for real-time predictions.

### Problem Statement:
Banks need an automated system to determine loan approval eligibility based on customer details like income, credit history, and loan amount. The objective is to build a predictive model to classify loan applications as approved or rejected.

### 🔹Solution:
Used Random Forest Classifier with hyperparameter tuning to optimize model performance.

Implemented Logistic Regression with feature selection for better interpretability.

Handled missing values and outliers in the dataset.

Evaluated model using Precision, Recall, and F1-Score.

Deployed using Flask, where users can enter loan details to check eligibility.


## 
### 3.[Credit Scoring & Customer Segmentation](CreditScoringSegmentation/)
## 📌 Project Details

This project applies K-Means clustering to segment customers based on their credit scores. It helps financial institutions categorize customers into different risk groups for better decision-making, loan approvals, and personalized financial products. The project includes data preprocessing, clustering analysis, and interactive visualizations for insights.

### Problem Statement:
Financial institutions require a credit scoring model to assess customers' creditworthiness and segment them into different risk categories. This helps in personalized loan offerings and risk mitigation.

### 🔹 Solution:

Used K-Means Clustering for customer segmentation based on spending behavior and credit history.

Built a Credit Score column using FICO formula using the other columns.

Determined the optimal number of clusters using the Elbow Method.

Visualized customer segments using a Scatter Plot with different colors representing different clusters
1) Excellent
2) Good
3) Low
4) Very Low


