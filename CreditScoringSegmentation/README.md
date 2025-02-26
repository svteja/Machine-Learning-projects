## 📌 Project Implementation
Developed a K-Means clustering model to segment customers based on credit scores, helping financial institutions assess risk profiles and improve decision-making. Engineered features from customer financial data to create meaningful clusters, allowing banks to categorize applicants effectively.

### How Will This Project Help?
This project assists banks and financial institutions in identifying high-risk and low-risk customers, optimizing credit offerings, and reducing financial risk through data-driven customer segmentation.

Resources Used

📌 Packages: pandas, numpy, matplotlib, seaborn, plotly etc.

📌 Dataset: credit_scoring.csv

### Exploratory Data Analysis (EDA) and Data Cleaning
1️⃣ Created new column Credit score using FICO formula.

2️⃣ Mapping the  categorical features like Education leveland employment status.

✔ EDA Insights:

Used bar plots, histograms, and scatter plots to analyze credit score distributions.
![Credit utilization ratio](https://github.com/user-attachments/assets/422eb8e6-0d5e-416c-ac64-84f9d2776ae2)
![Loan amount distubution](https://github.com/user-attachments/assets/cc1f7785-19ea-4289-a02e-23ab8b2cebdb)

Identified trends in income, spending behavior, and default probability.

Feature Engineering

📌 Feature Selection: Used Credit Score as the primary clustering feature.

### K-Means Clustering Implementation

🔄 Applied K-Means clustering with 4 clusters to segment customers based on their credit scores.

📌 Cluster Interpretation:

Cluster 0: High Credit Score (Low-Risk Customers) ✅(Green)

Cluster 1: Moderate Credit Score (Medium-Risk Customers)(Red)

Cluster 2: Low Credit Score (High-Risk Customers) ❌(Blue)

Cluster 3: Very Low Credit Score (Critical Risk Customers) 🚨(Yellow)
![Clusters](https://github.com/user-attachments/assets/4afbacd9-153f-4bf6-b30d-9b2deab21e98)


📌 Used Elbow Method to determine the optimal number of clusters.

![Elbow_Curve](https://github.com/user-attachments/assets/64798e5f-b915-4fb1-b121-f2d6a2147a19)


✔ Key Insights:

Identified customer groups based on credit behavior and risk levels.

Helps banks in loan approvals, credit limit assignments, and personalized financial services.

Final Model Output

📌 Predicts customer segmentation based on their credit score and financial behavior.

📌 Assigns each customer to one of four credit risk categories, helping financial institutions optimize lending decisions.

🚀 This project enhances risk assessment, improves financial decision-making, and enables banks to segment customers more efficiently. 🎯
