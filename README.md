# 💳 Financial Fraud Detection using Machine Learning

## 📖 Project Overview
This project builds a high-performance fraud detection system using advanced feature engineering, SMOTE balancing, and machine learning models to identify fraudulent financial transactions.

The goal is to accurately classify transactions as fraud or non-fraud while minimizing financial risk.

---

## 🎯 Problem Statement
To detect fraudulent transactions by analyzing:
- Transaction type
- Transaction amount
- Account balance changes
- Engineered balance-difference features

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- SMOTE (Imbalanced Learning)
- Matplotlib & Seaborn
- SHAP (Model Explainability)

---

## ⚙️ Methodology

1. Exploratory Data Analysis (EDA)
2. Feature Engineering
   - org_diff
   - dest_diff
   - amount_log
   - zero balance indicators
   - one-hot encoding
3. Handling Class Imbalance using SMOTE
4. Train-Test Split (Stratified 80/20)
5. Model Training:
   - Logistic Regression
   - Random Forest
   - XGBoost
6. Model Evaluation:
   - Precision
   - Recall
   - F1-Score
   - ROC-AUC
   - PR-AUC
7. SHAP Explainability

---

## 📊 Model Performance

### 🏆 Best Model: XGBoost

- Precision: **99.13%**
- Recall: **99.56%**
- F1-Score: **99.34%**
- ROC-AUC: **99.99%**
- PR-AUC: **99.95%**

XGBoost achieved the highest recall and PR-AUC, making it the most effective fraud detection model.

---

## 🧠 Key Fraud Indicators

- Origin balance difference (org_diff)
- Log-transformed transaction amount
- Zero-balance behavior
- CASH_OUT & TRANSFER transaction types
- Abnormal balance drops

---

## 💼 Business Impact

- Reduces financial losses
- Improves fraud detection recall
- Enables real-time risk scoring
- Supports scalable fraud prevention systems

---

## 📂 Project Structure

