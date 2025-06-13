# Loan_Approval_Prediction
# Loan Approval Prediction using Machine Learning

This project aims to predict whether a loan application will be approved or not approved based on applicant and financial information. By building a machine learning model, banks and financial institutions can automate the approval process, reduce risk, and make faster, more consistent decisions.
Problem Statement
Banks receive a high volume of loan applications daily. Manually reviewing each application is slow, error-prone, and inconsistent. This project provides a machine learning solution to automatically predict the approval status of a loan application using historical data.
________________________________________
# Objectives
•	Clean and preprocess raw loan application data
•	Perform Exploratory Data Analysis (EDA) to uncover patterns
•	Train multiple classification models
•	Identify the best-performing model
•	Analyze important features influencing approval decisions
Dataset Overview
The dataset includes the following types of features:
•	Personal Information: age, gender, education, employment status
•	Financial Data: income, loan amount, loan-to-income ratio
•	Loan Details: purpose (intent), home ownership, previous defaults
•	Target Variable: loan_status ("Approved" or "Not Approved")
________________________________________
# Data Preprocessing
•	Encoding: Applied binary, ordinal, and one-hot encoding for categorical variables
•	Outlier Treatment: Handled extreme values (e.g., unrealistic ages)
•	Feature Scaling: Used RobustScaler to normalize numeric features
Exploratory Data Analysis (EDA)
•	Visualized relationships between features and loan approval status
•	Used bar plots, pie charts, and heatmaps to identify patterns
•	Detected high-impact features like income ratio and default history
________________________________________
# Models Used
The following machine learning models were trained and compared:
•	Logistic Regression
•	Random Forest
•	LightGBM
•	CatBoost
•	XGBoost (best performer)
________________________________________
# Best Model
XGBoost achieved the highest accuracy:
✅ 93.46% accuracy – meaning the model correctly predicts loan approval status about 93 times out of 100.
Feature Importance
Top features influencing approval:
•	loan_percent_income (loan burden vs. income)
•	previous_loan_defaults_on_file
•	loan_intent and person_home_ownership
________________________________________
# Results & Benefits
•	Automates the loan approval process
•	Reduces manual workload
•	Improves decision speed and consistency
•	Offers transparency into why applications are accepted or rejected
________________________________________
# How to Run
1.	Clone the repository
2.	Open main.ipynb in Jupyter Notebook or VS Code
3.	Run all cells step-by-step to reproduce results
Requirements
•	Python 3.x
•	Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, lightgbm, catboost
________________________________________
# Future Improvements
•	Add credit score or transaction history if available
•	Deploy model via API for real-time scoring
•	Apply fairness checks to ensure unbiased decisions
Author
Project by [Atefah Hassani]
Presentation Link: https://www.canva.com/design/DAGprGNzBWg/OP2NK6hBlStWD3AU7ptpJQ/edit?utm_content=DAGprGNzBWg&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton 
For inquiries or collaboration, contact: Atefah.hassani@gmail.com

