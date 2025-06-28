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

#  Results
Best model: Random Forest Regressor

R² Score: 0.85+

Feature importance showed smoking and BMI had the most influence on cost

# Key Learnings
Data preprocessing and feature encoding are crucial for model performance

Random Forest performed better than linear models due to non-linear relationships

Strong correlation between smoking and higher insurance charges

# Future Improvements
Add more real-world features (e.g., health conditions)

Deploy model using Flask / Streamlit for interactive web app

Integrate with cloud-based data pipelines

