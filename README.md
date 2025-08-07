# Breast Cancer Recurrence Prediction – Logistic Regression

This project focuses on predicting breast cancer recurrence using logistic regression models. The dataset includes various tumor features, and the goal is to identify whether a recurrence is likely.

## What This Project Covers

-> Used summary statistics, correlation checks, and visualizations to understand feature relationships  
-> Performed label encoding on the categorical outcome variable  
-> Identified multicollinearity and removed redundant features  
-> Highlighted that the dataset is imbalanced (non-recurrence > recurrence)

## Models and Results

-> Logistic Regression with 1 feature (mean_area): Showed high accuracy but failed to detect recurrence cases  
-> Logistic Regression with 12 features: Improved performance but still missed many recurrence cases  
-> Forward Feature Selection: Chose 'mean_radius' as best predictor; high accuracy but 0 recall  
-> Regularization: No improvement in model performance  
-> Feature Scaling: Boosted recall significantly (from 0 to 1), making the model more useful for detecting recurrence  
-> Custom Cost Function: Same prediction results, but with modified loss calculation

## Key Learnings

-> High accuracy can be misleading in imbalanced datasets  
-> Feature scaling can greatly improve recall in binary classification  
-> Single-feature models may perform well on paper but fail to detect minority class  
-> Balanced performance is more important than just accuracy in medical use cases

## Files Included

-> assignment2_sumath.ipynb: Full notebook with code and results  
-> assignment_2_sumath.pdf: Final report summary  
-> README.md: This project summary

## Author

Sumath Chandra Kille  
