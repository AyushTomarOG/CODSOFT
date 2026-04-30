# Movie Rating Prediction using Machine Learning

This project aims to predict movie ratings using machine learning techniques based on features such as genre, duration, votes, release year, and cast information.

---

## Overview

The dataset used is the IMDb India Movies dataset, which contains real-world movie data. Due to inconsistencies and missing values, extensive data preprocessing and feature engineering were required before building the model.

---

## Workflow

* Data Cleaning:

  * Handled missing values selectively
  * Cleaned and converted Year, Duration, and Votes into numeric format
* Feature Engineering:

  * Extracted year from textual format
  * Created a new feature `Actor_Count` to represent cast size
  * Encoded categorical features such as Genre
* Model Building:

  * Implemented Linear Regression as a baseline model
  * Improved performance using Random Forest Regressor
* Model Evaluation:

  * Evaluated using Mean Squared Error (MSE) and R² Score

---

## Results

* Final Model: Random Forest Regressor
* R² Score: ~0.41
* Mean Squared Error (MSE): ~1.10

---

## Key Learnings

* Feature engineering plays a crucial role in improving model performance
* Real-world datasets require careful preprocessing and cleaning
* Ensemble models capture complex patterns better than linear models

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

---

## Future Improvements

* Hyperparameter tuning for further optimization
* Incorporating actor/director popularity features
* Experimenting with advanced models such as Gradient Boosting
