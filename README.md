#🕵️‍♀️ Fraud Detection in Online Transactions
This project focuses on detecting fraudulent transactions in mobile-based payment systems using machine learning models. It aims to help financial institutions reduce losses and secure customer transactions by accurately predicting fraudulent activity.

#📌 Problem Statement
Online payment fraud is a major issue in the financial industry, causing significant financial losses. The objective of this project is to build a machine learning model that can distinguish between genuine and fraudulent transactions based on transaction patterns and user behavior.
#Key Objectives
Explore and preprocess transaction data

Analyze patterns of fraud using visualizations

Train and compare different machine learning models

Evaluate model performance using key metrics

Analyze financial impact of model decisions

Provide actionable business insights

🗃️ Dataset
The dataset contains simulated mobile transaction records with the following key features:

step – Hour of the transaction

type – Type of transaction (e.g., CASH_OUT, TRANSFER)

amount – Transaction amount

oldbalanceOrg, newbalanceOrig – Sender's balance before and after transaction

oldbalanceDest, newbalanceDest – Receiver's balance before and after transaction

isFraud – Flag indicating whether a transaction is fraudulent

🔍 Exploratory Data Analysis (EDA)
Distribution of transaction types

Amount trends across transaction types

Correlation between features

Fraud patterns by transaction type and amount

Visualizations of fraud frequency and balances
#Model Building
Applied and compared the following models:

Logistic Regression

Random Forest Classifier

XGBoost Classifier

Gradient Boosting

📈 Evaluation Metrics
Used metrics for imbalanced classification:

Precision

Recall

F1-score

ROC-AUC Curve

Confusion Matrix

💸 Financial Impact Analysis
Calculated:

True Positive (TP): Correctly identified frauds → Potential Savings

False Negative (FN): Missed frauds → Potential Loss

Net Profit = Savings - Losses

📊 Results
Best model: Logistic Regression

High Recall and ROC-AUC for fraud class

Clear trade-off between precision and recall handled via threshold tuning

🛠️ Tools & Technologies
Python

Pandas, NumPy

Seaborn, Matplotlib

Scikit-learn

XGBoost

Jupyter Notebook

📦 Project Structure

fraud-detection/

│

├── data/                # Dataset files

├── notebooks/           # EDA and model building notebooks

├── visuals/             # Plots and graphs

├── model/               # Saved models (pickle files)

├── utils/               # Helper functions

├── README.md            # Project overview

└── fraud_detection.ipynb # Main notebook




