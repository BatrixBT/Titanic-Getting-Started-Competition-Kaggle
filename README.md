# Titanic Survival Prediction Analysis

This repository contains a machine learning project aimed at predicting the survival of passengers on the Titanic using various classification techniques.

## Overview

In this analysis, I explore the Titanic dataset, visualize the distribution of key features such as age, gender, and passenger class, and train several machine learning models to predict passenger survival. I used a stacking classifier approach, combining predictions from CatBoost, XGBoost, and Random Forest classifiers, with a Support Vector Classifier (SVC) as the final model.

## Data

The Titanic dataset used in this project is divided into three CSV files:
- `train.csv` - Contains data for training the model, including the target variable 'Survived'.
- `test.csv` - Contains data for testing and generating predictions.
- `gender_submission.csv` - Provides a sample submission format.

## Libraries Used

- `pandas` for data manipulation
- `numpy` for numerical operations
- `scikit-learn` for machine learning models and preprocessing
- `catboost` for CatBoostClassifier
- `xgboost` for XGBoostClassifier
- `matplotlib` and `seaborn` for data visualization

After training and evaluating the models, the Stacked Model achieves an accuracy of 0.8407 ± 0.0229.

Additionally, I ranked in the Top 6% of participants, or Top 774 out of 14,840 users, in the Titanic Getting started Kaggle competition.

This is a link to the [Titanic competition on Kaggle](https://www.kaggle.com/competitions/titanic).
You can view my Kaggle profile [here](https://www.kaggle.com/nejczavodnik).

 
