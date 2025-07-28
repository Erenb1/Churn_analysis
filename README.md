# Churn_analysis
# 🔁 Telecom Customer Churn Prediction

Predicting customer churn in the telecom industry using machine learning — a complete end-to-end project involving preprocessing, modeling, tuning, and recommendations.

---

## 📌 Problem Statement

Customer churn — when a customer stops using a service — is a critical metric for telecom companies. The goal of this project is to **predict which customers are most likely to churn**, enabling the company to intervene early and retain them.

---

## 📂 Project Structure

- `churn_prediction.ipynb`: Main notebook with all code and explanations
- `data/`: Dataset used (Telco Customer Churn from Kaggle)
- `README.md`: Project overview

---

## 🔍 Tools & Techniques Used

- **Languages:** Python
- **Libraries:** pandas, numpy, matplotlib, seaborn, sklearn
- **Techniques:** 
  - Data Cleaning & Encoding
  - Feature Engineering
  - Pipeline with ColumnTransformer
  - Train/Test Split & Scaling
  - Model Evaluation (ROC AUC)
  - Hyperparameter Tuning with GridSearchCV
  - Final Recommendations

---

## 📊 Models Trained

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier ✅ *(Best AUC: 0.849)*

---

## 📈 Evaluation Metric

- **Primary Metric**: ROC AUC Score  
- Reason: Better for imbalanced binary classification

---

## ✅ Key Findings & Recommendations

- Customers paying with **electronic checks** are more likely to churn — consider more secure or modern payment methods (e.g. crypto).
- Customers with **higher initial bills** and **no long-term contracts** churn more — offer discounts or loyalty rewards.
- **Month-to-month users** are the most at-risk — incentivize them to switch to long-term plans.

---

## 💡 What I Learned

- How to build and optimize machine learning pipelines with `sklearn`
- The power of **ROC AUC** as a metric for real-world imbalance problems
- Practical feature engineering and preprocessing techniques
- The importance of business understanding in turning ML insights into action

---

## 🚀 How to Run This Project

1. Clone this repo  
   `git clone https://github.com/yourusername/telecom-churn-prediction.git`

2. Run the Jupyter Notebook  
   `jupyter notebook churn_prediction.ipynb`

---

## 📁 Dataset

> [Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)  
Contains customer demographics, account info, services signed up for, and churn status.

---

## 👤 About Me

This is my **first end-to-end machine learning project**!  
I'm a student passionate about machine learning and data science, and I'm actively looking for **internship opportunities** where I can grow and contribute.

Let's connect on [LinkedIn]
(https://www.linkedin.com/in/erenali-balc%C4%B1karde%C5%9Fler-5b7440357/)

---

## ⭐️ If you found this project helpful, feel free to star the repo!

