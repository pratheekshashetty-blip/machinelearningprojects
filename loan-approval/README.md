Loan Approval Prediction

Machine learning model that predicts whether a loan application will be approved based on applicant financial and demographic features.

Project Overview

This project builds a machine learning classification model to predict loan approval decisions based on applicant information.
Financial institutions process large numbers of loan applications and must assess the risk associated with each applicant. By analyzing historical loan data, machine learning models can identify patterns that help determine whether a loan is likely to be approved.
The goal of this project is to train models that classify applications as approved or rejected.

Dataset

The dataset contains information about loan applicants including financial, employment, and demographic attributes.

Key features include:
- Gender
- Marital Status
- Education
- Applicant Income
- Co-applicant Income
- Loan Amount
- Loan Term
- Credit History
- Property Area

Target variable:
Loan_Status

1 → Loan Approved

0 → Loan Not Approved

Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Machine Learning Workflow
1. Data Exploration
Inspect dataset structure
Check for missing values
Analyze feature distributions

2. Data Preprocessing
Handle missing values
Encode categorical variables
Feature scaling where required

3. Model Training
Models used include:
Logistic Regression
Random Forest Classifier

4. Model Evaluation
Model performance is evaluated using:
Accuracy Score
Confusion Matrix
Classification Report
