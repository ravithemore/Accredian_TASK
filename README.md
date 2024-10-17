# Fraud Detection Project

## Repository Overview

This repository contains code and data for a project on predicting fraudulent transactions using machine learning models. The project involves data loading, cleaning, exploratory data analysis (EDA), visualization, and building a predictive model to detect fraudulent transactions.

## Files in the Repository
- `Data Dictionary.txt`: Contains a description of the features in the dataset.
- `LICENSE`: The license for the project.
- `README.md`: This README file, explaining the project structure and details.
- `predicting fraudulent transactions.ipynb`: The Jupyter notebook file where data preprocessing, EDA, and model building are performed.

## Data Description
The dataset used for this project contains information about financial transactions, including the following features:
- **step**: Time step in the data.
- **type**: Type of transaction (e.g., PAYMENT, TRANSFER).
- **amount**: The transaction amount.
- **nameorig**: The customer initiating the transaction.
- **oldbalanceorig**: Initial balance before the transaction.
- **newbalanceorig**: New balance after the transaction.
- **namedest**: The recipient of the transaction.
- **oldbalancedest**: Initial balance of the recipient before the transaction.
- **newbalancedest**: New balance of the recipient after the transaction.
- **isFraud**: Whether the transaction was flagged as fraud (1 for fraud, 0 for non-fraud).
- **isFlaggedFraud**: Whether the transaction was flagged by the system due to threshold triggers.

## Steps in the Notebook

## 🚀 Key Features

1. **Transaction Classification** 🏦  
   The system classifies each transaction as either fraudulent or genuine based on historical data, helping to prevent financial losses.

2. **Machine Learning Models** 🤖  
   Implements various machine learning models such as:
   - **Random Forest** 🌲
   - **Logistic Regression** 📊
   - **XGBoost** 🚀
   These models are trained to detect subtle patterns of fraudulent behavior.

3. **Data Preprocessing** 🧹  
   The project includes comprehensive data preprocessing techniques, including:
   - Handling missing values
   - Feature scaling
   - Dealing with class imbalance using techniques like **SMOTE**.

4. **Model Evaluation** 📈  
   After training the models, the system evaluates their performance using metrics like:
   - **Accuracy**
   - **Precision**
   - **Recall**
   - **F1-Score**
   - **ROC-AUC Score**

## 🛠️ Technologies Used

- **Programming Language**: Python 🐍
- **Libraries**:
  - Pandas 🐼
  - NumPy 🔢
  - Scikit-learn 📘
  - XGBoost 🚀
  - Matplotlib & Seaborn 📊 (for data visualization)
