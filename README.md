# 📞 Telecom Customer Churn Prediction

A data science project focused on predicting customer churn in the telecom industry using machine learning techniques, specifically logistic regression.

---

## 📌 Problem Statement

Churn is a major problem in the telecom industry. Losing customers leads to loss in revenue. The goal of this project is to **analyze customer data**, identify key factors contributing to churn, and build a **predictive model** that helps telecom companies **retain customers**.

---

## 🧠 Project Objectives

- Understand customer behavior and features leading to churn.
- Perform Exploratory Data Analysis (EDA) to identify trends.
- Build a churn prediction model using Logistic Regression.
- Evaluate model performance using metrics like accuracy, precision, recall, and ROC-AUC.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**
- Jupyter Notebook

---

## 🗃️ Dataset

The dataset used includes customer demographics, services availed, contract details, and churn information. It contains features such as:

- `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- `tenure`, `PhoneService`, `InternetService`
- `MonthlyCharges`, `TotalCharges`
- `Churn` (target)

> 📌 Dataset is assumed to be already cleaned or cleaned during preprocessing steps.

---

## 📊 Exploratory Data Analysis (EDA)

Performed EDA to understand:
- Distribution of churn across features
- Correlations between tenure/charges and churn
- Influence of services and contract types on churn

Visual tools used:
- Bar plots
- Histograms
- Heatmaps

---

## 🤖 Model Used

- **Logistic Regression**
    - Chosen for its interpretability and efficiency.
    - Coefficients help understand feature importance.
    - Trained on processed numerical and categorical features.

> Future scope: add more models like Random Forest, XGBoost, SVM.

---

## 📈 Model Evaluation

Metrics used:
- Accuracy
- Confusion Matrix
- Precision, Recall, F1-Score
- ROC-AUC Curve (can be added for deeper insights)

---
