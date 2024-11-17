# Credit Score Classification

## Overview

This project focuses on classifying credit scores based on various financial features such as income, credit utilization, debt, and payment history. The model uses machine learning techniques to predict an individual's credit score category (Poor, Standard, Good). The dataset used is sourced from [Kaggle: Credit Score Classification](https://www.kaggle.com/datasets/parisrohan/credit-score-classification/data).

## Project Structure

- **Data Preprocessing**: The dataset undergoes data cleaning, feature engineering, and transformation to create meaningful features for the model.
- **Feature Engineering**: Includes creating interaction features, ratios, and bins, and handling missing values and outliers.
- **Modeling**: The project uses Logistic Regression with hyperparameter tuning and cross-validation to predict credit scores.
- **Evaluation**: Model performance is evaluated using accuracy, precision, recall, F1 score, and a confusion matrix.

## Requirements

The project requires the following Python libraries:
- `pyspark`
- `kagglehub`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`
