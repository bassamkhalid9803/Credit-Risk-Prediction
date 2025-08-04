# Credit Risk Prediction

This project uses machine learning to predict whether a loan applicant is likely to **default on a loan**, based on demographic and financial data. The dataset is sourced from the **Loan Prediction Problem Dataset** on Kaggle.

## Dataset

The dataset includes features like:

- Gender, Marital Status, Dependents
- Education Level
- Applicant Income and Coapplicant Income
- Loan Amount and Loan Term
- Credit History
- Property Area

The target variable is:
- `Loan_Status`: (Y = Approved, N = Not Approved)

## Objectives

- Clean and handle missing values appropriately
- Visualize key features (Loan Amount, Education, Income)
- Train binary classification models:
  - Logistic Regression
  - Decision Tree
- Evaluate using accuracy and confusion matrix

## Results

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 79%      |
| Decision Tree       | 69%      |

## Visualizations

- Loan Amount Distribution
- Education vs Loan Status
- Applicant Income Distribution

## Tools Used

- Python (Pandas, NumPy, Seaborn, Matplotlib, scikit-learn)
- Jupyter Notebook

## 📁 Files

- `credit_risk_model.ipynb` — Full code with training and evaluation
- `train.csv`, `test.csv` — Original dataset (Kaggle)
- `README.md` — Project overview

## 📎 Credits

- [Loan Prediction Problem Dataset – Kaggle](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)

