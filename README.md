
# 💳 Credit Card Fraud Detection (ML Project)

This project uses **Logistic Regression** and **SMOTE** to detect fraudulent credit card transactions in a highly imbalanced dataset.

---

## 📦 Dataset

- **Original Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- The original dataset is over 150MB and can't be uploaded to GitHub directly.
- For demonstration purposes, this repository includes a small sample: `sample_creditcard.csv`

> To run the full analysis, download the complete dataset from the Kaggle link above and place `creditcard.csv` in the project directory.

---

## 🧠 Techniques Used

- Data preprocessing with `StandardScaler`
- Handling class imbalance using `SMOTE` (Synthetic Minority Oversampling Technique)
- Model training with **Logistic Regression**
- Evaluation using:
  - Confusion Matrix
  - Precision, Recall, F1-Score
  - ROC-AUC Score

---

## 📈 Results

| Metric         | Value     |
|----------------|-----------|
| Accuracy       | 97%       |
| Recall (Fraud) | 92%       |
| Precision      | 6%        |
| ROC-AUC        | 0.9785    |

> Recall is prioritized over precision due to the nature of fraud detection (better to catch more frauds even if some false positives occur).

---

## 📁 Files

- `fraud_detection.ipynb` – Jupyter Notebook with the full ML pipeline
- `sample_creditcard.csv` – A 1000-row sample of the dataset
- `requirements.txt` – Required Python libraries

---

## ▶️ Run the Project

```bash
pip install -r requirements.txt
```

Open the notebook in Jupyter or Colab and run all cells.

---

## 🧠 Author

- **Name:** Diptaraj Sinha  
- **GitHub:** [@yourusername](https://github.com/DiptarajSinha)  
- **LinkedIn:** [linkedin.com/in/yourprofile](https://linkedin.com/in/diptaraj-sinha-b2270b256)

---
