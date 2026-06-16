# Credit Card Fraud Detection using Machine Learning
## Overview
Developed a machine learning classification model to detect fraudulent credit card transactions using historical transaction data.
The project focuses on handling highly imbalanced datasets and optimizing fraud detection using precision, recall and F1-score.

---
## Problem Statement

Credit card fraud detection is challenging due to the extremely low number of fraudulent transactions compared to legitimate transactions.
The objective is to build a model that can identify fraudulent transactions while minimizing false alarms.

---
## Dataset

Dataset contains:
- Time
- Transaction Amount
- V1-V28 anonymized features
- Class (Target)
Class:
- 0 → Legitimate transaction
- 1 → Fraudulent transaction
---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---
## Machine Learning Workflow
1. Data loading and exploration
2. Exploratory Data Analysis
3. Data preprocessing
4. Handling class imbalance
5. Model training
6. Model evaluation
---

## Models Implemented
- Logistic Regression
- Random Forest Classifier

---

## Evaluation Metrics

Accuracy is not used as the primary metric because of class imbalance.
Models are evaluated using:
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC

---

## Results

Random Forest achieved strong performance with high precision and recall in detecting fraudulent transactions.

---

## Future Improvements

- Hyperparameter tuning
- XGBoost implementation
- Real-time fraud prediction API
