# Employee Turnover Prediction using Logistic Regression

## Project Overview

Employee turnover is a major challenge for organizations as frequent employee resignations increase recruitment costs, disrupt projects, and lead to the loss of skilled talent.

This project uses **Supervised Machine Learning** to predict whether an employee is likely to leave or stay in a company based on various work-related factors.

The project implements Logistic Regression and explores the impact of L1 and L2 regularization on model performance.

## Problem Statement

To develop a machine learning classification model that predicts employee turnover using employee-related attributes such as job satisfaction, salary, age, work-life balance, training hours, annual bonus, and other workplace factors.

## Objectives

- Build a baseline Logistic Regression model.
- Implement L1 (Lasso) regularization.
- Implement L2 (Ridge) regularization.
- Evaluate model performance using classification metrics.
- Compare the models and identify the best-performing approach.

## Dataset Description

The dataset contains employee-related attributes, including:

- Job Satisfaction
- Performance Rating
- Years at Company
- Work-Life Balance
- Distance From Home
- Monthly Income
- Education Level
- Age
- Number of Companies Worked
- Employee Role
- Annual Bonus
- Training Hours
- Department
- Engineered features

**Target Variable: Employee_Turnover**

- `0` – Employee Stayed
- `1` – Employee Left

## Technologies & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Machine Learning Workflow

1. Dataset Loading and Exploration
2. Feature and Target Separation
3. Train-Test Split
4. Baseline Logistic Regression
5. L1 Regularization
6. L2 Regularization
7. Model Evaluation
8. Performance Comparison

## Models Implemented

### 1. Baseline Logistic Regression
A basic Logistic Regression classifier used as the initial model.

### 2. L1 Regularization (Lasso)
Applies L1 regularization to reduce unnecessary feature coefficients and perform feature selection.

### 3. L2 Regularization (Ridge)
Applies L2 regularization to shrink model coefficients and help control overfitting.

## Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report

## Initial Model Results

| Model | Accuracy |
|---|---:|
| Baseline Logistic Regression | 85.93% |
| L1 Regularized Logistic Regression | 87.04% |
| L2 Regularized Logistic Regression | 85.93% |

*These are the results recorded in the current notebook run. They should be treated as preliminary until the baseline and regularization settings are made comparable.*

## Key Learning Outcomes

- Understanding Supervised Machine Learning.
- Implementing Logistic Regression for binary classification.
- Understanding L1 and L2 regularization.
- Evaluating classification models.
- Comparing model performance using evaluation metrics.

## How to Run the Project

1. Clone this repository.
2. Install the required dependencies.
3. Open the Jupyter Notebook.
4. Run the notebook cells in sequence.

## Project Status

Completed as a Supervised Machine Learning assignment project.

## Author

**Anushka Kushwah**
