# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using various machine learning algorithms. The goal is to develop a model that can accurately identify fraudulent transactions and help prevent financial loss for credit card companies and customers.

## Table of Contents

- [Introduction](#introduction)
- [Libraries Used](#libraries-used)
- [Data Preprocessing](#data-preprocessing)
- [Data Exploration](#data-exploration)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

The objective of this project is to build a robust fraud detection system for credit card transactions. The dataset contains information about various transactions, including features like time, amount, and class (fraudulent or not). By utilizing machine learning algorithms, we aim to create a model that can accurately predict whether a transaction is fraudulent or not.

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn
- catboost
- lightgbm
- xgboost

## Data Preprocessing

In this stage, we load the dataset using pandas from a CSV file. We perform basic data cleaning tasks, such as checking for missing values and dropping any rows with missing data. We also explore the dataset to gain insights into its structure and distribution.

## Data Exploration

In this section, we analyze the data to understand its characteristics and distributions. We visualize the class distribution to determine the data's imbalance. Additionally, we plot the density of transactions over time for both fraudulent and non-fraudulent transactions. This helps us identify any patterns or anomalies in the transaction data.

## Model Training and Evaluation

To detect credit card fraud, we employ various machine learning algorithms. We train and evaluate the following models:

- Random Forest Classifier
- AdaBoost Classifier
- CatBoost Classifier
- Support Vector Machine (SVM)
- LightGBM Classifier
- XGBoost Classifier

We use evaluation metrics like ROC AUC score to assess the performance of each model and select the best one for fraud detection.

## Usage

To use this project, follow these steps:

1. Clone the repository.
2. Install the required libraries mentioned in the `requirements.txt` file.
3. Download the credit card fraud dataset.
4. Run the Jupyter Notebook or Python script to preprocess the data, train the models, and evaluate their performance.
5. Adjust the hyperparameters, algorithms, or feature engineering techniques based on your requirements.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.