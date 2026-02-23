# Employee Turnover Prediction

## 📌 Project Overview
This project predicts employee turnover using Logistic Regression.  
The goal is to classify whether an employee is likely to leave the organization.

## 📊 Dataset
The dataset contains 1350 employee records with 15 numerical features including:
- Job Satisfaction
- Performance Rating
- Years at Company
- Monthly Income
- Annual Bonus
- Training Hours
- Work-Life Balance
- Department
- and engineered features like interaction terms

Target Variable:
- Employee_Turnover (0 = Stay, 1 = Leave)

## 🧠 Models Used
1. Logistic Regression (Baseline)
2. Logistic Regression with L1 Regularization (Lasso using LogisticRegressionCV)

## 📈 Model Performance

Baseline Logistic Regression:
- Accuracy: 85.9%
- Recall: 81.6%
- Precision: 87.17%

L1 Regularized Logistic Regression:
- Accuracy: 85.9%
- Recall: 81.6%
- Precision: 87.17%

## ⚙️ Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn

## 🚀 Key Learnings
- Train-test split strategy
- Model evaluation metrics (Accuracy, Recall, Precision)
- Regularization using L1 penalty
- Cross-validation using LogisticRegressionCV

---
