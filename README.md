# Loan Approval System

This project contains a Jupyter notebook for analyzing loan approval data and training machine learning models to predict whether a loan will be approved.

## Files

- `31_loan_approval.ipynb` - main analysis notebook
- `loan_approval_data.csv` - dataset used in the notebook
- `requirements.txt` - Python packages required to run the notebook

## Overview

The notebook performs:

- data loading and preprocessing
- missing value handling
- exploratory data analysis (EDA)
- encoding categorical variables
- feature scaling
- model training and evaluation for Logistic Regression, KNN, and Naive Bayes

## Setup

1. Create a Python virtual environment.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open `31_loan_approval.ipynb` in Jupyter Notebook or JupyterLab.

## Usage

Run the notebook cells sequentially to reproduce the data processing, feature engineering, and model evaluation steps.

## Notes

- The dataset is loaded from `loan_approval_data.csv`.
- The notebook uses `scikit-learn` for model training and evaluation.
