# 💳 Loan Default Prediction & Credit Risk Analysis

## 📌 Overview

This project focuses on predicting loan approval using machine learning techniques and analyzing key financial factors that influence credit risk.

The goal is to build an end-to-end pipeline covering data analysis, feature engineering, model training, and business insights relevant to real-world banking systems.

---

## 🧠 Problem Statement

Financial institutions must assess whether a loan applicant is likely to repay or default. This project aims to predict loan approval based on applicant data such as income, credit score, employment status, and loan details.

---

## 📊 Dataset

* ~2000 records
* Features include:

  * Age
  * Income
  * Credit Score
  * Loan Amount
  * Loan Term
  * Employment Status
* Target:

  * `Loan_Approved` (0 = Rejected, 1 = Approved)

---

## ⚙️ Key Steps

### 🔹 Data Preprocessing

* No missing values (clean dataset)
* Encoded categorical variables (Employment Status)

### 🔹 Exploratory Data Analysis

* Loan approval distribution analysis
* Credit Score vs Loan Approval
* Income vs Loan Amount
* Approval rate by employment status
* Correlation heatmap

### 🔹 Feature Engineering

* Created **Income-to-Loan Ratio**

  * Helps measure financial risk
  * Lower ratio indicates higher risk

---

## 🤖 Models Used

### 1. Logistic Regression

* Accuracy: ~91.7%
* ROC-AUC: ~0.97

### 2. Random Forest (Best Model)

* Accuracy: ~99.5%
* ROC-AUC: ~1.00

---

## 📈 Model Evaluation

* Confusion Matrix
* ROC Curve comparison
* Cross-validation
* Feature importance analysis

---

## 🔍 Key Insights

* **Credit Score is the strongest predictor**
  Approved applicants had significantly higher credit scores

* **Income-to-Loan Ratio is a critical risk indicator**
  Higher ratios indicate better repayment capacity

* **Employment status impacts approval likelihood**
  Employed applicants show higher approval rates

* **Random Forest outperformed Logistic Regression**
  It captures non-linear relationships between financial features

---

## 🏁 Conclusion

This project demonstrates how machine learning can be applied to credit risk assessment by combining data analysis, feature engineering, and model comparison.

The results highlight the importance of financial indicators such as credit score, income, and borrowing behavior in loan approval decisions.

---

## 🚀 Future Improvements

* Use advanced models like XGBoost / LightGBM
* Handle class imbalance with SMOTE
* Hyperparameter tuning (GridSearchCV)
* Deploy as a web app (Streamlit / Flask)

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 👩‍💻 Author

Shailaja Shettar

