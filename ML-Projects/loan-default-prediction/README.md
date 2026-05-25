# Loan Default Prediction using Machine Learning

## Problem Statement
Predict whether a customer will default on a loan to help financial institutions minimize risk.

---

## Dataset
- Source: Kaggle Credit Risk Dataset
- Features include income, employment, loan details, and credit history

---

## Approach

### 1. Data Preprocessing
- Missing value imputation (median)
- One-hot encoding for categorical variables
- Label encoding for ordinal features
- Feature scaling using StandardScaler

### 2. Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

### 3. Evaluation Metrics
- Recall (primary metric)
- Precision
- ROC-AUC

---

## Key Results

- Logistic Regression with threshold tuning improved recall from ~52% to ~71%
- KNN showed high precision but lower recall
- SVM achieved higher AUC but slightly lower recall than Logistic Regression

---

## Final Model

**Logistic Regression with threshold tuning**

Chosen for its ability to maximize recall and identify high-risk applicants.

---

## Business Impact

- Enables early identification of high-risk customers
- Helps reduce financial losses due to loan defaults
- Supports data-driven decision making

---

## Conclusion

The model improves risk detection by focusing on recall, ensuring better identification of defaulters while maintaining practical usability.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
