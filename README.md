# Overview
This project aims to predict the individual medical insurance costs billed by health insurance companies based on key features such as age, sex, BMI, number of children, smoking status, and region. The goal is to build a regression model that can accurately estimate charges and help insurance providers better assess risk and pricing.

# Objective
To develop and evaluate a machine learning regression model using real-world data to predict medical insurance charges based on demographic and lifestyle features.

# Dataset
Source: Kaggle - Medical Cost Personal Dataset

# Features:
age, sex, bmi, children, smoker, region

Target: charges

# Tools & Libraries
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn (Linear Regression, Random Forest, etc.)

Jupyter Notebook

# Workflow
Data Exploration & Cleaning

Checked for missing values, outliers

Converted categorical data using label/one-hot encoding

EDA (Exploratory Data Analysis)

Visualized distributions and correlations

Identified strong relationships (e.g., smoker vs charges)

Model Building

Trained multiple models: Linear Regression, Random Forest, SVR

Tuned hyperparameters using GridSearchCV

Evaluation

Metrics: R² Score, MAE, RMSE

Visualized prediction performance

# Key Learnings
Data preprocessing and feature encoding are crucial for model performance

Random Forest performed better than linear models due to non-linear relationships

Strong correlation between smoking and higher insurance charges

# Future Improvements
Add more real-world features (e.g., health conditions)

Deploy model using Flask / Streamlit for interactive web app

Integrate with cloud-based data pipelines

#  Results
Best model: Random Forest Regressor

R² Score: 0.85+

Feature importance showed smoking and BMI had the most influence on cost

<img width="570" alt="Screenshot 2025-06-28 at 4 31 53 PM" src="https://github.com/user-attachments/assets/4ac977b2-9bd7-4bf5-a406-6990ccffb847" />
<img width="621" alt="Screenshot 2025-06-28 at 4 31 31 PM" src="https://github.com/user-attachments/assets/20e5b65f-3ca8-45b6-91b5-aeaa3e503bea" />
<img width="953" alt="Screenshot 2025-06-28 at 4 32 25 PM" src="https://github.com/user-attachments/assets/328f8567-80c9-4541-a350-54ceece59096" />
