# Fraud Detection System using Machine Learning

## 📌 Business Problem
Financial fraud causes significant losses to institutions. The goal of this project is to detect fraudulent transactions while minimizing false negatives, as missing fraud is more costly than falsely flagging legitimate transactions.

---

## 📊 Dataset
- Highly imbalanced dataset
- Fraud transactions ≈ 0.17%
- Features anonymized for privacy

---

## 🧠 Approach
### Unsupervised Anomaly Detection
- Isolation Forest
- One-Class SVM
- Local Outlier Factor

### Supervised Learning
- XGBoost with class-weighted learning
- Stratified train–test split

---

## 📈 Evaluation
Accuracy is misleading due to class imbalance.  
Primary metrics used:
- Recall
- Precision
- F1-score
- Confusion Matrix

---


