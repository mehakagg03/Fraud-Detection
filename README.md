# Fraud-Detection-Model

## 📌 Project Overview

This project focuses on detecting fraudulent financial transactions using machine learning techniques. The goal is to build a predictive model that can accurately classify whether a transaction is fraudulent or legitimate based on transaction details.
The project includes data exploration, visualization, preprocessing, model building, and evaluation using Logistic Regression.


## 🧠 Problem Statement

Financial fraud is a major issue in digital transactions. Manual detection is inefficient due to the high volume of data. This project aims to:

- Analyze transaction patterns

- Identify features strongly associated with fraud

- Build a machine learning model to detect fraudulent transactions


## 📉 Key Features:

- type – Transaction type

- amount – Transaction amount

- oldbalanceOrg, newbalanceOrig – Origin account balances

- oldbalanceDest, newbalanceDest – Destination account balances


## 🔍 Exploratory Data Analysis (EDA)

The notebook includes:

- Fraud vs non-fraud distribution analysis

- Fraud percentage in the dataset

- Fraud rate by transaction type

- Boxplots comparing transaction amount vs fraud

- Correlation analysis between numerical features

- Visualizations are created using Matplotlib and Seaborn.

## ⚙️ Data Preprocessing

- Categorical features encoded using OneHotEncoder

- Numerical features scaled using StandardScaler

- Combined preprocessing using ColumnTransformer

- Train-test split performed using train_test_split

## 🤖 Model Used

**Algorithm: Logistic Regression**

Implemented using a Scikit-learn Pipeline to ensure clean preprocessing and modeling

## 📊 Model Evaluation

The model is evaluated using:

- Confusion Matrix

- Classification Report (Precision, Recall, F1-Score)

These metrics help assess how well the model identifies fraudulent transactions.

## 🛠️ Technologies & Libraries

- Python

- Pandas, NumPy

- Matplotlib, Seaborn

- Scikit-learn
