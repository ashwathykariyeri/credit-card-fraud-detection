# Credit Card Fraud Detection Using Machine Learning
Credit Card Fraud Detection using Machine Learning

## Overview
This project compares three machine learning models for 
detecting credit card fraud using the ULB benchmark dataset.
Models compared: Logistic Regression, Decision Tree, Naive Bayes.

## Dataset
- **Used:** ULB Credit Card Fraud Detection Dataset
- **Link:** https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
- **Size:** 284,807 transactions, 492 fraud cases (0.17%)
- The dataset used in this project is publicly available on Kaggle.
**Download here:** https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
After downloading, place `creditcard.csv` in the same 
folder as the notebook before running.

### Datasets Evaluated but Rejected
- Credit Card Fraud 2025: https://www.kaggle.com/datasets/prince7489/credit-card-fraud-2025
  - Rejected: AUC ≈ 0.50 (no discriminative signal)
- Financial Transactions 2025: https://www.kaggle.com/datasets/aryan208/financial-transactions-dataset-for-fraud-detection
  - Rejected: AUC ≈ 0.50 (no discriminative signal)

## Results

| Model               | Precision | Recall | F1-Score | AUC-ROC |
|---------------------|-----------|--------|----------|---------|
| Logistic Regression | 0.8333    | 0.8163 | 0.8247   | 0.9710  |
| Decision Tree       | 0.4783    | 0.7857 | 0.5946   | 0.8689  |
| Naive Bayes         | 0.0991    | 0.8061 | 0.1765   | 0.9646  |

## Project Report
[Overleaf Report Link](https://www.overleaf.com/read/dgjypqytmfcr#53bb0d)

## How to Run
1. Download dataset from Kaggle link above
2. Install dependencies:
   pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
3. Open Jupyter Notebook:
   jupyter notebook fraud_detection.ipynb

## Figures
All generated figures are in the `figures/` folder:
- fig1_class_distribution.pdf
- fig2_amount_by_class.pdf
- fig3_correlation_heatmap.pdf
- fig4_confusion_matrices.pdf
- fig5_roc_curves.pdf
- fig6_feature_importance.pdf

## Course
**Professor:** Raja Hashim Ali  
**Project:** Credit Card Fraud Detection  
**Year:** 2025
