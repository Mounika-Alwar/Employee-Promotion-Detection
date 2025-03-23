# Employee-Promotion-Detection

## Table of Contents
1. Introduction
2. Dataset
3. Methodology
4. Features
5. Models
6. Results
7. Conclusion
8. Future-work

## Introduction
This project aims to predict whether an employee will be promoted based on various employee-specific details. The predictive task involves analyzing the given features and leveraging suitable machine learning algorithms to build an accurate and robust model for classification.

## Dataset
The dataset consists of 13 features and contains a total of 54,808 samples.

## Methodology
1. Data Import
2. Exploratory Data Analysis (EDA)
    - Handling Null Values
    - Duplicates Check
    - Handling Outliers
3. Data Visualization
4. Feature Engineering
5. Handling Categorical Variables
6. Resampling the data
7. Model Building
8. Hyperparameter Tuning
9. Feature Importance

## Features
1. education
2. department
3. region
4. recruitment_channel
5. no_of_trainings
6. length_of_service
7. awards_won?
8. previous_year_rating
9. training_effectiveness (engineered feature)
10. award_boost (engineered feature)

## Models
1. Logistic Regression
2. Linear SVC
3. K-Nearest Neighbors
4. Random Forest
5. Gradient Boosting Classifier

## Results
Logistic Regression | 0.62 
Linear SVC | 0.71 
K-Nearest Neighbors | 0.86 
Random Forest | 0.99 
Gradient Boosting Classifier | 0.83 

## Conclusion
The Gradient Boosting Classifier was tuned using RandomSearch CV to attain an accuracy of 97%. The features 'awards_won?' and 'department_Sales&Marketing' were found to have the most feature importance.

## Future Work
1. Collect more data to improve model performance.
2. Experiment with other machine learning algorithms.
3. Perform feature selection to reduce dimensionality.
4. Use techniques like ensemble learning to combine models.
