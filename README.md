# Credit Card Fraud Detection Using Machine Learning

## Overview
This project applies machine learning techniques to detect fraudulent credit card transactions using a publicly available dataset from Kaggle.

## Final Report

[Download the full report (PDF)](./docs/credit-card-fraud-detection-report.pdf)

## Dataset
- Source: [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) (ULB Machine Learning Group)
- Contains anonymized transaction data
- Highly imbalanced dataset with very few fraudulent transactions

## Methods
- Exploratory Data Analysis (EDA)
- Feature selection and scaling
- Logistic Regression
- Random Forest

## Evaluation
Models were evaluated using:
- Confusion Matrix
- Precision
- Recall
- F1-score

## Results
- Logistic Regression performed well overall but missed some fraudulent transactions
- Random Forest achieved better performance, particularly in recall and F1-score
- Random Forest was more effective at detecting fraud

## Key Takeaways
- Class imbalance significantly impacts model evaluation
- Accuracy alone is not a reliable metric
- Recall is critical for fraud detection problems

## Repository Structure
- [`eda.ipynb`](./notebooks/eda.ipynb) – Data analysis and modeling
- [`capstone.png`](./docs/images/capstone.png) – Model comparison results
- [LaTeX report](./docs/credit-card-fraud-detection-report.pdf) – Final project report

## Author
James D. Pinkston

## Development Setup

For environment setup and development workflow instructions, see:
[SETUP.md](./SETUP.md)
