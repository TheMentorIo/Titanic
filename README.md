# Titanic Survival Prediction

## Overview

This project involves building a machine learning model to predict survival on the Titanic based on various passenger features. The goal is to use classification techniques to determine the likelihood of survival and identify key factors that contributed to survival.

## Dataset

The dataset used for this project is the **Titanic dataset**, which contains information about passengers on the Titanic. It includes the following columns:

- **PassengerId**: Unique identifier for each passenger.
- **Pclass**: Passenger class (1st, 2nd, or 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Ticket**: Ticket number.
- **Fare**: Fare paid by the passenger.
- **Embarked**: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
- **Survived**: Whether the passenger survived (1) or not (0).

## Objectives

1. **Data Exploration**:
   - Load and examine the dataset.
   - Handle missing values and outliers.
   - Explore the distribution of features and target variable.

2. **Feature Engineering**:
   - Create new features if necessary (e.g., family size, title extraction).
   - Encode categorical variables and normalize numerical features.

3. **Model Building**:
   - Develop and compare various classification models (e.g., Logistic Regression, Decision Trees, Random Forest, Support Vector Machine).
   - Train models using training data and evaluate them using cross-validation.

4. **Model Evaluation**:
   - Assess model performance using metrics such as accuracy, precision, recall, F1 score, and ROC AUC.
   - Select the best-performing model based on evaluation metrics.

5. **Insights and Recommendations**:
   - Identify key features influencing survival chances.
   - Provide recommendations for improving survival prediction accuracy.
