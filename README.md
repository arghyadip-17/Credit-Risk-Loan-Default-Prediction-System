# 💳 Credit Risk & Loan Default Prediction System

## 📌 Project Overview
This project focuses on predicting **loan default risk** using machine learning techniques.  
The goal is to help financial institutions identify **high-risk and low-risk customers** before approving loans, thereby reducing financial losses.

The system analyzes customer demographic, financial, and credit-related features to predict whether a loan applicant is likely to **default (1)** or **repay (0)**.

---

## 🎯 Objectives
- Predict loan default probability using ML models
- Identify factors that increase default risk
- Understand characteristics of low-risk customers
- Compare multiple machine learning models
- Improve prediction performance using evaluation metrics like **AUC, ROC, Accuracy**

---

## 🧠 Machine Learning Models Used
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

Each model is evaluated and compared using standard performance metrics.

---

## 📊 Dataset Description
The dataset contains customer-level loan information such as:
- Applicant income
- Credit history
- Loan amount
- Loan term
- Employment details
- Property area
- Loan status (Target Variable)

**Target Variable:**
- `Loan_Status`
  - `1` → Non-Defaulter (Low Risk)
  - `0` → Defaulter (High Risk)

---

## ⚙️ Project Workflow
1. Data Loading & Exploration  
2. Data Cleaning & Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature Encoding & Scaling  
5. Model Training  
6. Model Evaluation  
7. Model Comparison  
8. Business Insights & Recommendations  

---

## 📈 Model Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

Special focus is given to **AUC score**, as it is crucial for credit risk modeling.

---

## 🔍 Key Insights
### Factors Increasing Default Risk
- Poor or missing credit history  
- Low applicant income  
- High loan amount relative to income  
- Unstable employment  
- Short loan tenure  

### Characteristics of Low-Risk Customers
- Good credit history  
- Stable and higher income  
- Lower loan-to-income ratio  
- Longer loan tenure  
- Urban or semi-urban property location  

---

## 🛠️ Technologies Used
- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost (optional)

---

