# Predicting Hospital Readmissions: A Data Science Pipeline

This repository contains a Jupyter Notebook that develops a machine learning model to predict the likelihood of hospital readmissions for patients.

## Overview

The goal of this project is to address the problem of unplanned 30-day readmissions, a key focus of the Hospital Readmissions Reduction Program (HRRP). By identifying patients at high risk for readmission, healthcare organizations can proactively create post-discharge care plans to prevent readmissions and improve patient outcomes.

## Pipeline

The notebook implements a comprehensive data science pipeline, covering the following steps:

- Data Loading and Exploration
- Importing necessary libraries (Pandas, NumPy, Matplotlib, Scikit-learn)
- Loading the hospital readmission dataset
- Exploratory data analysis (EDA) to understand data characteristics and identify potential issues
- Data Preprocessing
- Handling missing values
- Converting categorical features to numerical representations
- Feature scaling to ensure consistent ranges
- Model Training and Evaluation

Training multiple machine learning models:

- Logistic Regression
- K-Nearest Neighbors
- Random Forest
- XGBoost
- Evaluating model performance using metrics like accuracy, precision, recall, and F1-score
- Model Selection and Tuning

Selecting the best-performing model (XGBoost in this case)

- Hyperparameter tuning to optimize XGBoost's performance
- Prediction and Deployment
- Using the final XGBoost model to predict readmission likelihood for new patients
- Discussing deployment strategies for integration into healthcare systems

## Key Findings

- XGBoost outperformed other models in predicting readmissions.
- Identified key features associated with high readmission risk.
- Demonstrated potential for proactive care planning to reduce readmissions.

## Repository Contents

- README.md (this file)
- hospital_readmission_prediction.ipynb (Jupyter Notebook containing the project code)
