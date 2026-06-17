# Customer Churn Prediction using Machine Learning

## 📖 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. Churn occurs when a customer stops using a company's products or services.

The objective of this project is to build a Machine Learning model that can predict whether a customer is likely to churn based on demographic and behavioral information. This helps businesses identify at-risk customers and take proactive retention measures.

---

## 🎯 Problem Statement

Predict whether a customer will:

- Stay with the company (No Churn)
- Leave the company (Churn)

This is a Binary Classification Problem.

---

## 📂 Dataset Information

The dataset contains customer information such as:

- Gender
- Senior Citizen Status
- Partner Status
- Dependents
- Tenure
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn Status

Target Variable:

```text
Churn
0 = No
1 = Yes
```

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Pickle

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Customer Churn Distribution
- Gender vs Churn
- Senior Citizen vs Churn
- Contract Type vs Churn
- Internet Service vs Churn
- Payment Method vs Churn
- Monthly Charges Analysis
- Tenure Analysis

Key insights were extracted to understand customer behavior and churn patterns.

---

## 🧹 Data Preprocessing

The following preprocessing steps were applied:

- Data type conversion
- Missing value handling
- Removal of irrelevant features
- Target variable encoding
- One-Hot Encoding
- Feature Scaling

---

## 🚀 Feature Engineering

A new feature was created:

### AvgMonthlySpend

```python
AvgMonthlySpend = TotalCharges / (tenure + 1)
```

This feature represents the average spending behavior of a customer.

---

## 🤖 Machine Learning Models Used

The following classification algorithms were trained and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. K-Nearest Neighbors (KNN)
4. Random Forest Classifier
5. Support Vector Machine (SVM)
6. Gaussian Naive Bayes

---

## 📊 Model Comparison

All models were compared using accuracy scores.

### Best Performing Model

✅ Logistic Regression

Accuracy Achieved:

```text
79.74%
```

---

## 🔧 Hyperparameter Tuning

GridSearchCV was applied to optimize the Logistic Regression model.

Parameters tuned:

- C
- Solver
- Class Weight

The tuned model achieved performance comparable to the baseline model.

---

## 📈 Model Evaluation

Evaluation metrics used:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1 Score
- Classification Report

---

## 💡 Business Insights

Key findings from the analysis:

- Customers with Month-to-Month contracts show the highest churn rate.
- Customers using Fiber Optic internet services tend to churn more frequently.
- Higher Monthly Charges are associated with increased churn.
- Long-term customers are less likely to leave the service.
- Customer retention strategies should focus on high-risk customer groups.

---

## 💾 Model Deployment Preparation

The final trained model and scaler were saved using Pickle:

```text
customer_churn_model.pkl
scaler.pkl
```

These files can be reused without retraining the model.

---

## 📌 Project Workflow

1. Data Collection
2. Data Exploration
3. Data Cleaning
4. Feature Engineering
5. Data Encoding
6. Feature Scaling
7. Model Training
8. Model Comparison
9. Hyperparameter Tuning
10. Model Evaluation
11. Model Saving
12. Prediction on New Data

---

## 👩‍💻 Author

Seema Gupta

Machine Learning Enthusiast | Python | SQL | Data Analytics | AI