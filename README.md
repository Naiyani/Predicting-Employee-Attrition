# Predicting-Employee-Attrition

This project applies supervised machine learning techniques to predict employee attrition using the IBM HR Analytics dataset.
The goal is to identify employees at risk of leaving by prioritizing recall under class imbalance while maintaining model interpretability.

## Models Used

LASSO Logistic Regression

XGBoost (with and without SMOTE)

Stacked Ensemble Model

Feedforward Neural Network (baseline comparison)

## Key Focus

Handling class imbalance

Recall-driven evaluation

Interpretable feature analysis

## Key Findings

Accuracy alone is insufficient for attrition prediction.

Recall-focused models perform better at identifying at-risk employees.

The stacked ensemble achieved the best balance between recall, precision, and F1-score.

Overtime, stock options, job level, and monthly income were the strongest predictors of attrition.

## Tools & Technologies

Python, Scikit-learn

XGBoost

Imbalanced-learn (SMOTE)

TensorFlow/Keras

SHAP for interpretability

## Dataset

IBM HR Analytics Employee Attrition Dataset
