## 📌 Project Implemanation
Developed a machine learning model to predict loan approval for applicants based on key factors such as gender, income, employment history, dependents, credit history, and property area.
Engineered features from applicant data to evaluate loan eligibility, ensuring more accurate lending decisions.

## How Will This Project Help?
This project assists banks and financial institutions in evaluating loan applicants more efficiently, reducing the chances of loan defaults, and improving decision-making in loan approvals.

## Resources Used
📌 Packages: pandas, numpy, sklearn, matplotlib, seaborn, xgboost, imbalanced-learn, Flask, pickle

📌 Dataset: loan_data.csv

## Exploratory Data Analysis (EDA) and Data Cleaning
  Removed Unwanted Columns: Eliminated unnecessary features that did not contribute to loan approval decisions.

### ✔ Handled Missing Values:
1️⃣ Filled NaN values in Credit_History and Self_Employed based on income and education level.

2️⃣ Updated 'Dependents' column by imputing missing values using mode-based imputation.

### ✔ Categorical Data Cleaning:
1️⃣ Standardized gender labels (M → Male, F → Female).

2️⃣ Handled inconsistent entries in Married, Property_Area, and Education.

3️⃣ Removed duplicate records to maintain data integrity.

### ✔ EDA Insights:

Used bar plots, histograms, and correlation heatmaps to analyze feature relationships.
![Screenshot 2025-02-25 112314](https://github.com/user-attachments/assets/c58d969f-0591-4697-90a6-399ce6e489c6)
![Screenshot 2025-02-25 112334](https://github.com/user-attachments/assets/912427c8-5bad-4424-b9f9-b5609c2ba8c6)
![Screenshot 2025-02-25 112434](https://github.com/user-attachments/assets/4cc9fff3-bc54-446f-961c-df4f389b8573)

Identified income distribution, loan amounts, and approval trends across different applicant categories.
![Screenshot 2025-02-25 112355](https://github.com/user-attachments/assets/0c898fac-f718-4673-86fc-4ef40efada75)
![Screenshot 2025-02-25 112416](https://github.com/user-attachments/assets/fd8ad526-3ea4-43cd-bccb-fd1a2db005a8)

### Feature Engineering
📌 Derived new features: Created income-to-loan ratio to assess applicant financial stability.

📌 Categorical Encoding: Applied  One-Hot Encoding to categorical variables.

📌 Feature Scaling: Applied StandardScaler to normalize numerical features.

## Pipeline Creation
🔄 Automated pipeline for encoding, scaling and model training to ensure a structured workflow.
![Screenshot 2025-02-25 112205](https://github.com/user-attachments/assets/8c5fa9ea-4c0f-4d21-93f8-09a5665554de)

## Deployment
🚀 Model deployed on a local Flask server using a pickle file for real-time loan approval predictions.
![Screenshot (73)](https://github.com/user-attachments/assets/50b92c2e-709f-4bb9-a1e8-c71c4f25ffcf)


💻 Web Interface: Developed a user-friendly SBI-themed HTML & CSS UI with dropdowns, cards, and input fields for seamless interaction.

## Evaluation & Performance Metrics
✔ Model evaluation techniques: ROC curves, confusion matrices, classification reports.
![Screenshot 2025-02-25 112231](https://github.com/user-attachments/assets/4e611fe6-e0c9-42cc-987a-8093e960beb4)


✔ Key Metrics: Accuracy, Precision, Recall, F1-Score, AUC-ROC.

✔ Hyperparameter Tuning: Applied GridSearchCV for model optimization.

## Model Prediction
📌 Final Model Output: Predicts whether a loan will be approved or rejected based on applicant details.

📌 Provides a clear decision: Loan Approved ✅ or Loan Not Approved ❌ to assist lenders in making informed decisions.

🚀 This project enhances loan approval efficiency, reduces manual processing time, and minimizes financial risk for banks. 🎯
