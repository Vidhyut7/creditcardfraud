# creditcardfraud

# Credit Card Fraud Detection

This project implements a machine learning pipeline to detect fraudulent credit card transactions using supervised learning techniques. It leverages a publicly available dataset of anonymized credit card transactions and applies preprocessing, feature engineering, and model training for binary classification.

## Dataset

- The dataset used contains credit card transactions made by European cardholders in September 2013.
- It includes 284,807 transactions, of which 492 are fraudulent.
- All features except for `Time` and `Amount` are PCA-transformed components (V1 to V28).
- The data is highly imbalanced, with frauds representing 0.172% of all transactions.

## Objective

The primary objective is to accurately classify transactions as fraudulent or legitimate using various machine learning algorithms and evaluation techniques.

## Workflow

1. Data Loading and Exploration
2. Preprocessing:
   - Handling imbalance with under-sampling and over-sampling (SMOTE)
   - Feature scaling
3. Model Training:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - XGBoost
4. Evaluation:
   - Confusion Matrix
   - Precision, Recall, F1-Score
   - ROC Curve and AUC
5. Model Comparison

## Algorithms Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Area Under Curve (AUC)

## Results Summary

The project compares different classifiers on the basis of their ability to detect fraud. The models were evaluated using confusion matrices and AUC scores to account for class imbalance.


