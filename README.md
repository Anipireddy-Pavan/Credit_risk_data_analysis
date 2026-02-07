# Credit_risk_data_analysis
End-to-end customer credit risk analysis project using Python and machine learning to predict delinquency through data preprocessing, EDA, feature engineering, and decision tree modeling.

📌 Customer Credit Risk Analysis

Predicting Customer Delinquency Using Machine Learning

📖 Project Overview

This project focuses on analyzing customer financial and behavioral data to predict credit delinquency risk. Using a structured data analytics and machine learning pipeline, the goal is to help financial institutions identify high-risk customers early, reduce default losses, and improve credit decision-making.

The project demonstrates end-to-end data analytics skills, including data preprocessing, feature engineering, exploratory analysis, and predictive modeling.

📊 Dataset Summary

Total Records: 500 customers

Final Records After Outlier Removal: 420

Total Features: 19

Numerical: Age, Income, Credit Score, Utilization, Loan Balance, Debt Ratio, Missed Payments, Account Tenure

Categorical: Employment Status, Card Type, Location, 6-Month Payment History

Target Variable: Customer Delinquency Status (Binary)

✔ No missing values
✔ Clean and structured dataset

🔍 Exploratory Data Analysis (EDA)

Distribution analysis using histograms and boxplots

Correlation analysis revealed no single strong predictor, reinforcing the need for multivariate modeling

Weak correlations observed for income, credit score, and account tenure

🚨 Outlier Detection

Method Used: Interquartile Range (IQR)

Outliers Removed: 80 records (16%)

Key affected variables: Income, Credit Score, Age, Loan Balance

This step improved model stability and prediction accuracy.

🛠 Feature Engineering

Created a custom risk label based on:

More than 2 missed payments

Credit score below 600

Debt-to-income ratio above 40%

One-Hot Encoding for categorical variables

Ordinal mapping for 6-month payment history

🤖 Machine Learning Model
Model Used: Decision Tree Classifier

Why Decision Tree?

Easy to interpret decision logic

Handles non-linear relationships

No need for feature scaling

Provides feature importance insights

Hyperparameters:

Max Depth: 5

Minimum Samples Split: 20

Minimum Samples Leaf: 10

Train-Test Split: 80/20 (Stratified)

📈 Model Performance

Accuracy: 95%

High-Risk F1-Score: 97%

Low-Risk Recall: 100%

The model successfully identifies high-risk customers while ensuring no low-risk customers are wrongly classified.

📌 Key Business Insights

Enables early risk detection

Supports proactive credit risk management

Reduces financial losses due to defaults

Improves portfolio health and decision confidence

🧰 Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-Learn

Jupyter Notebook

📄 Project Files

Data preprocessing & EDA

Feature engineering pipeline

Machine learning model implementation

Performance evaluation

Presentation PDF (for executive-level insights)

👤 Author

Pavan Anipireddy
Aspiring Data Analyst | Machine Learning Enthusiast

📧 Email: anipireddypavan@gmail.com
