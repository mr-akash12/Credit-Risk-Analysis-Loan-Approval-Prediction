
# 🏦 Bank Credit-Risk-Analysis-Loan-Approval-Prediction

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)  
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn%2C%20XGBoost-orange)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)  
![License](https://img.shields.io/badge/License-MIT-yellow.svg)  
📌 Project Description 
This project focuses on building a Machine Learning model to predict bank loan approvals based on applicant details such as income, employment type, dependents, assets, loan amount, term, and credit score . The goal is to help banks and financial institutions automate the loan approval process, reduce risk and make data-driven decisions .
----
## 🎯 Objectives  
- Perform **Exploratory Data Analysis (EDA)** to identify key factors influencing loan approvals.  
- Build and compare **classification models** to predict loan status.  
- Evaluate models using **accuracy, precision, recall, F1-score, and ROC-AUC**.  
- Provide **business insights** to minimize loan default risk.  
---

## 📊 Dataset  
- **Rows:** 4269  
- **Features:** 12 (Applicant income, employment, assets, dependents, loan amount, term, CIBIL score, etc.)  
- **Target:** `loan_status` (Approved / Rejected)
- 
  ## 🔍 Exploratory Data Analysis  
- **Univariate Analysis:** Distribution of income, loan amount, and CIBIL score.  
- **Bivariate Analysis:** Loan approval trends by income vs loan amount, CIBIL vs loan approval.  
- **Correlation Heatmap:** Identified relationships between numeric features.  
- **Key Insight:** **CIBIL score, income, and loan-to-income ratio** strongly affect loan approval.
- ---

## 🤖 Machine Learning Models  
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting (XGBoost, LightGBM)
- ---

## 🛠 Tech Stack  
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
- 
## 📈 Results  
- Models compared on multiple metrics.  
- **Random Forest and Gradient Boosting** gave the best performance with balanced accuracy and recall.  
- Feature importance showed **CIBIL score, income, and loan amount** as the top predictors.
- 
- ## 📂 Project Structure
- ├── data/ # Dataset
├── notebooks/ # Jupyter notebooks for EDA & modeling
├── models/ # Trained ML models
├── src/ # Source code for preprocessing & training
├── README.md # Project documentation
└── requirements.txt # Dependencies


## 📸 Website Preview
Here are some snapshots of the aWebsite:
![image alt](https://github.com/mr-akash12/Credit-Risk-Analysis-Loan-Approval-Prediction/blob/main/Screenshot%202025-09-26%20022724.png)

## 🙌 Acknowledgements  
This project is inspired by real-world banking use cases of **credit risk analysis** and demonstrates how **machine learning** can enhance decision-making in financial institutions.  


