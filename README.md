# customer-churn-prediction-logistic-regression

# 📉 Customer Churn Prediction using Logistic Regression

This project aims to predict whether a customer will churn (leave) based on historical telecom customer data using machine learning — specifically, **Logistic Regression**.

---

## 📌 Problem Statement

Customer churn is a critical issue for subscription-based services. Predicting churn allows businesses to take proactive steps to retain customers. This project uses a labeled dataset to train a model that can classify customers as "churned" or "not churned."

---

## 🧠 Objectives

- Clean and preprocess customer data
- Perform feature encoding and exploration
- Train a Logistic Regression model
- Evaluate performance using classification metrics
- Interpret model predictions
- Deploy-ready Jupyter notebook for educational/demo use

---

## 🧰 Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Logistic Regression, train_test_split, metrics)
- Jupyter Notebook / Google Colab

---

## 📊 Dataset Overview

- Fields like `gender`, `Partner`, `Dependents`, `tenure`, `Contract`, etc.
- Binary target variable: `Churn` (Yes/No)

---

## 🧼 Data Preprocessing

- Replaced categorical values with numerical encoding (e.g., Male → 1, Female → 0)
- Handled missing/null values
- Removed outliers using standard techniques
- Feature selection and correlation analysis

---

## 🧪 Model Training

- Train/test split using `train_test_split()`
- Logistic Regression model from `sklearn.linear_model`
- Model trained on selected features

---

## ✅ Evaluation Metrics

- **Accuracy**
- **Precision & Recall**
- **F1-score**
- **Confusion Matrix**

These metrics help assess model performance in predicting churn vs. non-churn accurately.



## 📈 Results Summary

The Logistic Regression model showed promising performance with balanced precision and recall. This model is interpretable and suitable for business decision-making as a first-step churn predictor.


