Credit Card Fraud Detection Project

* Overview

This project aims to develop a credit card fraud detection system using machine learning techniques. With the rise of digital payments, the risk of fraud has increased, making effective detection methods essential. This project generates a synthetic dataset simulating credit card transactions, preprocesses the data, trains various machine learning models, and evaluates their performance.

* Features

Synthetic dataset generation with various transaction features.

Exploratory Data Analysis (EDA) to visualize transaction distributions and correlations.

Data preprocessing including cleaning, encoding, and scaling.

Implementation of machine learning models: Logistic Regression and Random Forest.

Performance evaluation using accuracy, precision, recall, and F1-score metrics.

* Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

* Dataset

The dataset contains 10,000 synthetic credit card transactions with the following features:

transaction_id: Unique identifier for each transaction.

amount: Transaction amount.

transaction_date: Date and time of the transaction.

merchant: Merchant where the transaction occurred.

cardholder_id: Identifier for the cardholder.

transaction_type: Type of transaction (e.g., Purchase, Cash Withdrawal, Transfer).

location: Location of the transaction.

is_fraud: Target variable indicating whether the transaction is fraudulent (0: Not Fraud, 1: Fraud).

The dataset is imbalanced, with only 5% of transactions labeled as fraudulent.

* Results

The project evaluates two models:

Logistic Regression: Accuracy of 94.80%

Random Forest: Accuracy of 94.70%

The Logistic Regression model was identified as the best model based on accuracy.

Conclusion

This project demonstrates a comprehensive approach to credit card fraud detection using machine learning. By leveraging synthetic data for demonstration, the methodology can be applied to real-world datasets for improved fraud detection systems. Insights gained from EDA inform feature selection and model choice, leading to more effective implementations.

