# Titanic Survival Prediction

This project builds a machine learning model to predict whether a passenger survived the Titanic disaster using Logistic Regression.

---

## Overview

The Titanic dataset contains passenger information such as age, gender, ticket class, and fare. The objective is to predict survival:

* 0 = Did not survive
* 1 = Survived

---

## Workflow

* Data Cleaning (handling missing values and dropping columns which have mostly NULL values)
* Feature Encoding (converting categorical variables to numerical)
* Feature Selection
* Creating new features from existing features for better results
* Model Training using Logistic Regression
* Model Evaluation (Accuracy and Confusion Matrix)

---

## Features Used

* Pclass
* Sex
* Age
* Fare
* SibSp
* Parch

---

## Model

* Logistic Regression

---

## Results

* Accuracy: ~88%

Confusion Matrix:

```
[[48  6]
 [ 5 31]]
```

---

## Key Learnings

* Data preprocessing significantly impacts model performance
* Feature engineering can improve results
* Simple models can perform well with well-prepared data

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

---

## Kaggle Notebook

https://www.kaggle.com/code/ayushtomarog/titanic-survival-prediction-logistic-regression

---

## How to Run

1. Clone the repository
2. Install dependencies:
   pip install pandas numpy scikit-learn
3. Run the notebook file (.ipynb)

---

## Future Improvements

* Would try advanced models such as Random Forest
* Perform hyperparameter tuning
* Improve feature engineering
