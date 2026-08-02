# Breast Cancer Classification

This project develops and compares machine-learning models for classifying breast tumour samples as malignant or benign from quantitative cell-nucleus features.

## Workflow

- exploratory analysis of feature distributions, correlations, missing values, and outliers;
- train/test splitting and feature standardisation;
- analysis of class imbalance and SMOTE-based resampling;
- PCA for dimensionality reduction and visual inspection;
- comparison of logistic regression, KNN, SVM, random forest, gradient boosting, and XGBoost;
- hyperparameter tuning and error analysis;
- interpretation of feature importance and model performance.

Particular attention is paid to recall for malignant cases because false-negative predictions are the more consequential error in a screening-style setting.

## Data

The notebook uses the [Breast Cancer Wisconsin (Diagnostic) dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data). Download `data.csv` from the source and place it in this directory before running the notebook.

## Notebook

[Open the analysis](analysis.ipynb)

The analysis is educational and must not be interpreted as a clinically validated diagnostic system.
