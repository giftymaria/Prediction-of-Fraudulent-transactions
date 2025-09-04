💳Fraud prevention powered by data-driven insights and machine learning

A machine learning project to detect fraudulent transactions using data cleaning, feature engineering, and predictive modeling.

 🔹 Project Highlights
- Data Cleaning: Outliers capped at 99th percentile, engineered features to handle multicollinearity.
- Model: Random Forest Classifier (100 estimators, max depth=10, balanced class weights).
- Performance: 
  - Accuracy: 99.9995%
  - Precision: 1.00
  - Recall: 99.6%
  - ROC AUC: 0.9997
  - Zero false positives (only 9 fraud cases missed out of 2,464).
- Key Predictors: Accounting errors (`errOrig`), balance changes (`deltaOrig`), transaction types (TRANSFER, CASH_OUT, PAYMENT), and transaction amounts.
- Prevention Measures: Real-time monitoring, anomaly detection, MFA for risky transactions, automated flagging.

🚀 Outcome
Developed a highly effective fraud detection system with near-perfect accuracy that maximizes fraud capture while minimizing customer disruption.
