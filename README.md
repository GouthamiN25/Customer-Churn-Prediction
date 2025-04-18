## 📊 Customer Churn Prediction Capstone
A Data Science Approach to Improving Customer Retention

## 🔍 Overview
This project focuses on predicting customer churn using the Telco Customer Churn dataset. The goal is to identify customers at risk of leaving and provide actionable insights to improve customer retention using a data-driven approach.

## 🧠 Problem Statement
Customer churn can significantly impact a company’s revenue and growth. This project aims to:

Build a classification model to predict churn (Yes/No)

Analyze customer behavior based on contract types, monthly charges, and service usage

Provide data-driven recommendations for reducing churn

## 🔧 Technologies Used
Languages: Python, SQL

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Models: Logistic Regression, Random Forest, Lasso Regression

Other Tools: SMOTE for class balancing, GridSearchCV for hyperparameter tuning

## 🔍 CRISP-DM Approach
Business Understanding: Churn impacts revenue and customer acquisition costs; predicting it helps retention.

Data Understanding: Used Telco dataset with customer demographics, contract, and service data.

Data Preparation: Cleaned data, handled missing values, encoded categorical features, and scaled continuous ones.

EDA: Analyzed relationships between churn and features like contract type, payment method, and monthly charges.

Modeling: Trained and compared multiple ML models. Addressed class imbalance using SMOTE.

Evaluation: Used ROC-AUC, accuracy, classification report, and confusion matrix for model validation.

## 📈 Key Insights
Customers with month-to-month contracts and higher monthly charges are more likely to churn.

Certain payment methods show higher churn patterns, highlighting user dissatisfaction.

Targeted retention strategies, discount offers, and promoting long-term contracts can improve retention.

## 📌 Recommendations
Personalize retention efforts for high-risk segments like month-to-month users or senior customers.

Offer incentives to encourage commitment to long-term plans.

Improve service experience, especially for fiber optic users, to reduce churn.

