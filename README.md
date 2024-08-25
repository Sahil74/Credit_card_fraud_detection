# Credit Card Fraud Detection

## Overview

This project aims to detect fraudulent transactions in credit card datasets using machine learning techniques. 
The dataset used contains information about various transactions, including details such as transaction amount, 
time, and other features. The goal is to identify and classify fraudulent transactions to help in fraud detection 
and prevention.

## Requirements

- Python 3.x
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn, imbalanced-learn, tensorflow
- pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn tensorflow

## Code Explanation

1. Data Loading and Preprocessing:
- Load the dataset and inspect its shape and structure.
- Drop unnecessary columns that do not contribute to the prediction model.
- Convert categorical features to numeric using one-hot encoding and frequency encoding.
- Extract date-time features from the transaction date and time.

2. Data Visualization:
- Visualize fraud and non-fraud cases per transaction category using bar plots.
- Plot the distribution of fraudulent transactions by hour and month.
- Create a correlation matrix heatmap to understand feature relationships.

3. Data Preparation:
- Handle imbalanced data using SMOTE (Synthetic Minority Over-sampling Technique).
- Normalize feature values using MinMaxScaler.
- Split the dataset into training and testing sets.

4. Model Building and Evaluation:
- Build a neural network model using TensorFlow/Keras with two hidden layers.
- Train the model and evaluate its performance on the test set.
- Predict fraudulent transactions and evaluate the model using classification metrics and confusion matrix.


