# 💳 Credit Card Fraud Detection (ML Project)

This project uses **Logistic Regression** and **SMOTE** to detect fraudulent credit card transactions in a highly imbalanced dataset.

## 📊 Dataset

- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 transactions with 492 frauds.
- Features are PCA-transformed (`V1` to `V28`) + `Time`, `Amount`

## 🧠 Model Summary

- Preprocessed with `StandardScaler`
- Balanced using `SMOTE` oversampling
- Trained with `LogisticRegression`
- Evaluated with:
  - Confusion matrix
  - Precision/Recall/F1
  - ROC-AUC score

### 🔍 Final Metrics

| Metric         | Value     |
|----------------|-----------|
| Accuracy       | 97%       |
| Recall (Fraud) | 92%       |
| Precision      | 6%        |
| ROC-AUC        | 0.9785    |

## 💡 Learnings

- Recall > Precision is acceptable in fraud detection
- SMOTE improves recall significantly
- ROC-AUC is more stable than accuracy on imbalanced data

## 🧪 Setup

```bash
pip install -r requirements.txt
