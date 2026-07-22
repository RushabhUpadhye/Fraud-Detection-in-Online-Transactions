# Fraud Detection in Online Transactions-
End-to-end Fraud Detection in Online Transactions using Machine Learning, Feature Engineering, Risk Scoring.


## Project Overview

This project develops an end-to-end Machine Learning solution to detect fraudulent online transactions for **PaySphere Digital Payments**. The objective is to identify fraudulent transactions while minimizing customer friction and supporting real-time fraud risk assessment.

The project follows a complete Data Science workflow, from data validation and exploratory analysis to model development, threshold tuning, fraud risk scoring, and business recommendations.

---

## Business Objective

The primary goals of this project are to:

- Detect fraudulent online transactions.
- Reduce financial losses caused by fraud.
- Improve operational efficiency for fraud analysts.
- Balance fraud prevention with customer experience.
- Build an explainable and interview-friendly machine learning solution.

---

## Dataset

The project uses a synthetic online transaction dataset containing customer, merchant, device, payment, and transaction-related information.

### Dataset Summary

- Total Transactions: **50,000**
- Problem Type: **Binary Classification**
- Target Variable: **is_fraud**

---

## Project Workflow

### Phase 1 – Dataset Understanding
- Dataset overview
- Data types
- Target identification
- Class distribution
- Numerical, categorical, datetime, and ID columns

### Phase 2 – Data Validation
- Primary key validation
- Duplicate detection
- Missing value analysis
- Business rule validation
- Timestamp validation
- Data quality assessment

### Phase 3 – Data Cleaning
- Missing value handling
- Duplicate removal
- Data type corrections
- Data consistency improvements

### Phase 4 – Fraud-Focused Exploratory Data Analysis
- Fraud distribution
- Transaction amount analysis
- Customer behavior
- Device analysis
- Merchant analysis
- Location analysis
- Temporal analysis
- Payment method analysis

### Phase 5 – Feature Engineering

Created fraud-specific features including:

- Transaction Velocity
- Average Historical Amount
- Amount Deviation Score
- Device Familiarity Score
- Device Change Flag
- Location Change Flag
- Merchant Risk Score
- Time of Day Risk
- Day of Week Risk
- High-Risk Payment Method Flag
- Combined Risk Index

### Phase 6 – Preprocessing
- One-Hot Encoding
- Feature Scaling
- Train-Test Split

### Phase 7 – Class Imbalance Handling
- Class Weight strategy

### Phase 8–10 – Model Building
- Logistic Regression
- Random Forest
- XGBoost

### Phase 11 – Model Comparison
Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- PR-AUC

### Phase 12 – Threshold Tuning
Multiple probability thresholds were evaluated to balance fraud detection and customer experience.

### Phase 13 – Final Model Analysis
- Confusion Matrix
- Feature Importance
- Fraud Drivers

### Phase 14 – Fraud Risk Scoring
Transactions were categorized into:

- Low Risk
- Medium Risk
- High Risk
- Very High Risk

### Phase 15 – Business Actions
Risk-based operational decisions:

- Low Risk → Approve
- Medium Risk → OTP Challenge
- High Risk → Manual Review
- Very High Risk → Hard Block

### Phase 16 – Business Recommendations
Recommendations were provided for:

- Fraud Risk Team
- Payments Engineering Team
- Customer Experience Team
- Data Science Team

---

## Machine Learning Models

The following supervised learning models were evaluated:

1. Logistic Regression
2. Random Forest
3. XGBoost

---

## Final Model

**Selected Model:** Logistic Regression

The final model was selected based on business-oriented evaluation metrics rather than overall accuracy.

Priority Metrics:

1. Recall
2. PR-AUC
3. F1 Score

Threshold tuning was performed to optimize fraud detection performance.

---

## Key Insights

- Device changes are strong indicators of fraud.
- Location changes significantly increase fraud risk.
- High IP risk scores are associated with fraudulent transactions.
- International transactions show higher fraud probability.
- Behavioral features improve fraud detection more than raw transaction amounts.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Power BI
- Jupyter Notebook

---

## Future Improvements

- Real-time fraud scoring deployment
- Device fingerprinting
- Geo-location distance features
- Continuous model retraining
- Streaming fraud detection

---

## Author

**Rushabh Upadhye**

Data Science Capstone Project

---

## Acknowledgement

This project was developed as part of a Data Science Capstone Program using the **PaySphere Digital Payments** fraud detection case study.
It demonstrates an end-to-end machine learning workflow for fraud analytics, from data validation to business recommendations.
