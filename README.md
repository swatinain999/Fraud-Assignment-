# Fraud-Assignment-
📌 Fraud Detection Assignment – Accredian Internship Screening
This project is a submission for the Accredian Data Science Internship screening assignment. The goal was to detect fraudulent transactions using a real-world financial dataset with over 6 million records.
✅ Objective
Develop a machine learning model to predict fraudulent financial transactions and extract meaningful insights to support proactive fraud prevention strategies.
🧠 Key Tasks Performed
Data cleaning (missing values, duplicates, outliers)

Feature engineering and one-hot encoding

Class imbalance handling with class weights

Model building using Random Forest

Evaluation using:

Classification Report

Confusion Matrix

ROC AUC Score (achieved 0.98)

Business insights and recommendations (Q1–Q8 answered)

📊 Dataset Overview
Rows: 6,362,620

Features: 10 (+ target)

Target Variable: isFraud (1 = fraud, 0 = normal)

Fraud Rate: ~0.13%

Transaction Types: PAYMENT, TRANSFER, CASH_OUT, etc.

🔍 Model Results (Sampled Data)
Precision (fraud): 0.98

Recall (fraud): 0.72

ROC AUC: 0.98

📌 Project Highlights
Reduced full dataset to a focused subset (TRANSFER, CASH_OUT) for better modeling.

Handled extreme class imbalance using class weights (no SMOTE).

Interpreted key fraud indicators using feature importance.

Answered all 8 business questions as per assignment requirements.

📁 Notebook
The full notebook contains:

Code and visualizations

Step-by-step explanations

Clearly marked answers to Q1–Q8 using Markdown cells

Install requirements: pandas, scikit-learn, matplotlib, seaborn

