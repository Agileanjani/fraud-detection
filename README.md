# Fraud Detection Project

This project detects fraudulent transactions in a financial dataset (~6.3M rows).
It explores:
- Data preprocessing & feature engineering
- Handling class imbalance
- Logistic Regression and Random Forest models
- Evaluation with ROC-AUC and PR-AUC
- Business insights & fraud prevention recommendations

### Files
- `Fraud_Detection_Accredian.ipynb` → Main Jupyter Notebook
- `Data Dictionary.txt` → Column definitions
- `Fraud_sample.csv` → Small sample dataset (for demo)

### Results
- Fraud is rare (~0.07%) and mostly involves TRANSFER → CASH-OUT patterns.
- Random Forest achieved higher PR-AUC than Logistic Regression.
- Key signals: transaction type, balance inconsistencies, and amount vs balance ratios.
