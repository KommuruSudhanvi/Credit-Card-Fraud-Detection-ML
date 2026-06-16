# Credit Card Fraud Detection using Machine Learning

## Overview

This project focuses on building a machine learning based system to classify credit card transactions as fraudulent or genuine.

The objective is to analyze transaction patterns and develop classification models capable of identifying fraudulent activities while handling the challenge of highly imbalanced data.

---

## Problem Statement

Credit card fraud detection is a binary classification problem where the goal is to predict whether a transaction is fraudulent or legitimate.

Since fraudulent transactions represent only a very small percentage of total transactions, accuracy alone is not a reliable evaluation metric. Therefore, the model performance is evaluated using precision, recall and F1-score.

---

## Dataset

Dataset Source: Kaggle - Credit Card Fraud Detection Dataset

The dataset contains transactions made by European cardholders in September 2013.

Dataset Details:

- Total transactions: 284,807
- Fraudulent transactions: 492
- Features: 30
- Target variable: Class

Feature Description:

- Time: Seconds elapsed between transactions
- V1 - V28: Anonymized features obtained using PCA transformation
- Amount: Transaction amount
- Class:
  - 0 → Genuine transaction
  - 1 → Fraudulent transaction

The dataset is highly imbalanced, making fraud detection a challenging classification problem.

---

## Project Workflow

The project follows the following pipeline:

1. Data Loading and Understanding
2. Exploratory Data Analysis (EDA)
3. Feature Analysis and Visualization
4. Data Preprocessing
5. Model Training
6. Model Evaluation
7. Performance Comparison

---

## Exploratory Data Analysis

Performed analysis includes:

- Understanding dataset structure
- Checking class distribution
- Visualizing transaction patterns
- Correlation analysis using heatmaps

---

## Data Preprocessing

Steps performed:

- Separating features and target variable
- Splitting data into training and testing sets
- Feature scaling using StandardScaler
- Preparing data for machine learning models

---

## Machine Learning Models Used

### Logistic Regression

Used as a baseline classification model for fraud detection.

### Random Forest Classifier

An ensemble learning algorithm used to capture complex patterns and improve classification performance.

---

## Model Evaluation

Since the dataset is highly imbalanced, evaluation is performed using:

- Precision
- Recall
- F1-score
- Confusion Matrix

These metrics provide better insight into how effectively fraudulent transactions are detected.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Future Improvements

Possible improvements:

- Implement advanced sampling techniques such as SMOTE
- Perform hyperparameter tuning
- Experiment with additional ML algorithms
- Deploy the model using a web framework

---

## Repository Structure
