Student Score Prediction
Machine learning model that predicts student exam scores based on study habits and academic-related factors.

Project Overview

This project applies machine learning regression techniques to predict student exam scores based on factors such as study time, attendance, and other academic attributes.
Educational institutions can use such models to better understand the factors that influence student performance and identify students who may require additional support.
The goal is to train a model that accurately predicts exam scores based on input features.

Dataset
The dataset contains information about students and their academic behavior.

Typical features include:

- Study Hours
- Attendance
- Previous Scores
- Assignments Completed
- Sleep Hours

Target variable:
Exam_Score – numerical value representing the student's final exam performance.

Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

Machine Learning Workflow
1. Data Exploration
Understand dataset structure
Analyze feature distributions
Check for missing values

2. Data Preprocessing
Handle missing values
Feature scaling using StandardScaler (for regression models)

3. Model Training
Regression models used:
Linear Regression
Ridge Regression
Lasso Regression

4. Model Evaluation
Model performance is evaluated using:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
