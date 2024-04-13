# Logistic Regression Analysis on Termite Discovery

## Overview
This directory contains notebooks that apply logistic regression to predict the probability of termite discovery based on various environmental and wood treatment factors.

## Dataset Context
The dataset features a combination of categorical and numerical variables, such as wood type, chemical treatments, and environmental factors, which influence termite discovery—a binary variable indicating whether termites were found.

## Model Implementation
We use the `LogisticRegression` class from `sklearn.linear_model`. This model is apt for binary classification tasks, estimating probabilities using a logistic function.

## Usage
- **Model Configuration**: Configure the logistic regression model with desired settings for solver, regularization, and iteration limits.
- **Model Training and Prediction**: Train the model with training data and make predictions; assess probability outputs using the `predict_proba` method.
- **Model Evaluation**: Evaluate the model's accuracy and interpret the confusion matrix to gauge performance.

## Key Concepts
- **Probability Estimation**: Logistic regression is particularly useful for scenarios where you want to estimate the likelihood of an event (e.g., termite discovery).
- **Categorical Outcome Modeling**: This approach is well-suited for binary or categorical outcome variables.

## How to Run
Follow the instructions in the Jupyter notebook to run the logistic regression analysis from data preprocessing to model evaluation.

## References
- Scikit-learn Logistic Regression documentation: [Scikit-learn Logistic Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
