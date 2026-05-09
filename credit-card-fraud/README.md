# Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset used is highly imbalanced, making fraud detection a challenging real-world classification problem.

---

## Overview

The objective of this project is to build a machine learning model capable of classifying transactions as either genuine or fraudulent based on transaction-related features.

The dataset contains anonymized transaction features (`V1` to `V28`), along with `Time`, `Amount`, and the target column `Class`.

* `Class = 0` → Genuine Transaction
* `Class = 1` → Fraudulent Transaction

---

## Workflow

* Data Loading and Exploration
* Handling Class Imbalance
* Feature Scaling using `StandardScaler`
* Train-Test Splitting with Stratification
* Model Training using:

  * Logistic Regression
  * SMOTE (Synthetic Minority Oversampling Technique)
* Model Evaluation using:

  * Precision
  * Recall
  * F1-score
  * Confusion Matrix

---

## Handling Imbalanced Data

The dataset was highly imbalanced, with fraudulent transactions representing only a very small portion of the data.

To improve fraud detection performance:

* SMOTE was applied to generate synthetic fraud samples
* Evaluation focused on Recall and F1-score rather than Accuracy

---

## Results

### Before SMOTE

* Fraud Recall: ~0.64
* Fraud Precision: ~0.83

### After SMOTE

* Fraud Recall: ~0.92
* Fraud Precision: ~0.06

The results demonstrated the tradeoff between fraud detection sensitivity and false positive rate.

---

## Key Learnings

* Accuracy is not reliable for highly imbalanced datasets
* Recall is a critical metric in fraud detection
* SMOTE improves fraud detection capability significantly
* Handling real-world imbalance is an important machine learning challenge

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Imbalanced-learn (SMOTE)

---

## Future Improvements

* Use Random Forest or XGBoost for better performance
* Tune classification thresholds
* Improve precision while maintaining high recall
* Perform hyperparameter tuning

---
