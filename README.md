🏦 Personal Loan Prediction Model

A machine learning project that predicts whether a customer is likely to accept a personal loan offer based on demographic and financial attributes.
This project uses Logistic Regression (LR) and Decision Tree (DT) models for supervised classification.

📌 Project Overview

Banks and financial institutions use predictive models to identify customers who are likely to accept personal loan offers.
This project explores customer behavior, builds ML models, and evaluates their performance.

The notebook includes:

Data loading & cleaning

Exploratory data analysis

Feature engineering

Model training (LR & DT)

Model evaluation and comparison

🔧 Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook

⚙️ Workflow Summary
1. Data Preprocessing

Handle missing values

Remove irrelevant columns

Normalize numerical features

Encode categorical variables

2. Model Training

Logistic Regression for baseline classification

Decision Tree Classifier for non-linear patterns

3. Evaluation Metrics

Accuracy

Confusion Matrix

Precision, Recall, F1-score

ROC Curve / AUC

📊 Results Summary

Logistic Regression provides a strong interpretable baseline.

Decision Tree captures deeper patterns and feature splits.

ROC/AUC is used to compare model performance.

(Fill in your final accuracy/AUC values here once model is trained.)

🚀 How to Run

Install dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn


Open the notebook:

jupyter notebook "LR and DT Advanced - Personal Loan Data.ipynb"


Run cells sequentially to reproduce results.

📁 Repository Structure
├── data/
│   └── personal_loan.csv
├── notebook/
│   └── LR and DT Advanced - Personal Loan Data.ipynb
├── models/
│   └── saved_models_here (optional)
└── README.md

📬 Future Improvements

Add Random Forest or XGBoost

Cross-validation

Model deployment using Flask
