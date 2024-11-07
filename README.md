# Customer Churn Analysis

## Overview

This project aims to predict customer churn for a bank using machine learning algorithms. We analyze a dataset of bank customers with attributes influencing their decision to stay or leave the service. Six algorithms were evaluated: Logistic Regression, Support Vector Machine (SVM), Decision Tree, Random Forest, Multi-Layer Perceptron (MLP), and XGBoost. The goal is to identify the best algorithm based on prediction accuracy and understand the factors affecting customer retention.

## Features

- **Dataset**: Contains 10,000 customers with 14 attributes (age, credit score, balance, tenure, etc.)
- **Algorithms Tested**: Logistic Regression, SVM, Decision Tree, Random Forest, MLP, and XGBoost
- **Focus**: Predict customer churn (Exited = 1) or retention (Exited = 0)

## Results

- **Best Model**: Multi-Layer Perceptron (MLP) with 84.5% accuracy and a macro average F1 score of 0.73.
- Other models like Random Forest, Decision Tree, and XGBoost performed similarly, but MLP showed the best balance between precision and recall.

## Future Improvements

- Collect more granular data such as customer feedback and churn reasons.
- Explore ensemble methods for better performance.
- Address issues of class imbalance and fairness in predictions.

## Skills

- Python
- Scikit-learn
- Matplotlib & Seaborn
- Exploratory Data Analysis (EDA)
- Machine Learning Model Evaluation
- Feature Engineering
