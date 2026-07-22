# Fraud Detection in Online Transactions
End-to-end machine learning project for detecting fraudulent online transactions using feature engineering, model comparison, threshold tuning, and fraud risk scoring.

## Executive Summary

This project presents an end-to-end machine learning solution for detecting fraudulent online transactions using the PaySphere Digital Payments case study. The workflow covers data validation, exploratory data analysis, feature engineering, model development, threshold tuning, fraud risk scoring, and business recommendations. The solution is designed to be accurate, explainable, and aligned with real-world fraud detection practices.

---

## Business Problem

Online payment fraud leads to significant financial losses and negatively impacts customer trust. The objective of this project is to identify fraudulent transactions while minimizing false alarms and maintaining a smooth customer experience. The solution aims to support proactive fraud prevention through data-driven risk assessment and operational decision-making.

---

## Methodology

* Performed comprehensive data validation and cleaning to improve data quality.
* Conducted fraud-focused exploratory data analysis to identify transaction patterns and risk factors.
* Engineered behavioral and risk-based features, including Transaction Velocity, Merchant Risk Score, Amount Deviation Score, Device Familiarity Score, and Combined Risk Index.
* Built and compared three machine learning models:

  * Logistic Regression
  * Random Forest
  * XGBoost
* Evaluated models using Recall, PR-AUC, F1 Score, Precision, and Accuracy.
* Applied threshold tuning to balance fraud detection performance with customer experience.
* Developed a fraud risk scoring framework and business action strategy based on prediction probabilities.

---

## Skills

* Python
* Pandas & NumPy
* Data Validation & Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning
* Logistic Regression
* Random Forest
* XGBoost
* Threshold Tuning
* Fraud Risk Scoring
* Model Evaluation
* Scikit-learn
* Matplotlib & Seaborn
* Business Analytics

---

## Results & Business Recommendation

* Compared multiple machine learning models and selected **Logistic Regression** as the final model based on fraud-focused evaluation metrics.
* Identified key fraud drivers, including location changes, device changes, IP/network risk, and historical fraud indicators.
* Created a four-level fraud risk scoring framework (Low, Medium, High, Very High Risk) to support operational decision-making.
* Recommended risk-based actions:

  * Low Risk → Approve
  * Medium Risk → OTP Challenge
  * High Risk → Manual Review
  * Very High Risk → Hard Block
* Proposed business recommendations for the Fraud Risk, Payments, Customer Experience, and Data Science teams to strengthen fraud prevention.

---

## Next Steps

* Deploy the trained model for real-time fraud detection.
* Continuously retrain the model using newly available transaction data.
* Incorporate additional behavioral and device-based features to improve detection performance.
* Integrate fraud monitoring dashboards for continuous performance tracking and operational insights.
