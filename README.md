 Customer Churn Prediction

Week 1: Exploratory Data Analysis

Dataset

Source: Telco Customer Churn (Kaggle)
Size: 7,043 customers, 21 features
Target: Predict customer churn (Yes/No)
Key Findings

Dataset Scale & Target Distribution: The dataset contains 7,043 customers across 21 features. The overall churn rate is approximately 26.5%, showing class imbalance where non-churned customers form the majority.
Missing Values: The TotalCharges column contained blank spaces/missing values, which were successfully converted to numeric types for clean evaluation.
Contract Type: Month-to-month contracts have a significantly higher churn rate compared to one-year or two-year contracts, where churn drops drastically.
Tenure: Newer customers (low tenure, typically under 12 months) are at the highest risk of leaving[cite: 1]. Churn probability declines as customer duration increases.
Setup

Open the Kaggle notebook or run locally: pip install pandas numpy matplotlib seaborn
