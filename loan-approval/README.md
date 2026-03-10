# Loan Approval Prediction

Machine learning model that predicts whether a loan application will be approved based on applicant financial and demographic features.

## Project Overview

This project builds a machine learning classification model to predict loan approval decisions based on applicant information.

Financial institutions process large numbers of loan applications and must assess the risk associated with each applicant. By analyzing historical loan data, machine learning models can identify patterns that help determine whether a loan is likely to be approved.

The goal of this project is to train models that classify applications as approved or rejected.

## Dataset

The dataset contains information about loan applicants including financial, employment, and demographic attributes.

Key features include:

- gender  
- marital status  
- education  
- applicant income  
- co-applicant income  
- loan amount  
- loan term  
- credit history  
- property area  

Target variable:

loan_status  

1 → loan approved  
0 → loan not approved  

## Tools and Libraries

- python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

## Machine Learning Workflow

### Data Exploration
- inspect dataset structure  
- check for missing values  
- analyze feature distributions  

### Data Preprocessing
- handle missing values  
- encode categorical variables  
- apply feature scaling when required  

### Model Training
- logistic regression  
- random forest classifier  

### Model Evaluation
- accuracy score  
- confusion matrix  
- classification report
