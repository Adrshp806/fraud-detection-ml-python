# Fraud Detection in Financial Transactions using Machine Learning

This project explores how machine learning can detect fraudulent transactions in financial datasets. It was developed as part of a master's degree project using a labeled dataset from Kaggle. The work includes data preprocessing, feature engineering, handling class imbalance, and evaluating multiple classification models.

---

## 🔗 Dataset

- **Source**: [Kaggle – Fraud Transaction Detection](https://www.kaggle.com/datasets/sanskar457/fraud-transaction-detection/data)
- **Note**: The dataset is not included in this repo. Please download it manually and place it in the `data/` folder.

---

## 📁 Project Structure
```text
fraud-detection-ml-python/
├── data/ # Dataset (not included)
├── notebooks/ # Jupyter notebook with full workflow
│ └── fraud_detection_analysis.ipynb
├── report/ # Final project documentation
│ ├── CA4U_14589_ADRSH.pdf
│ └── CA4U_14589_ADRSH.docx
├── src/ # (Optional) Python modules if separated
├── requirements.txt # Python dependencies
├── .gitignore # Files to exclude from Git
└── README.md # Project overview

---

## 🧠 Models Implemented

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

---

## ⚙️ Techniques Used

- Exploratory Data Analysis (EDA)
- Feature extraction from timestamps
- Standardization of numeric variables
- Handling imbalanced data (e.g., SMOTE)
- Evaluation metrics: Accuracy, Precision, Recall, F1-score
- Confusion matrices
- Model comparison and overfitting discussion

---

## 📈 Results Summary

| Model              | Accuracy | F1 Score | Notes                              |
|--------------------|----------|----------|------------------------------------|
| Random Forest      | 100%     | 1.00     | High performance, overfitting risk |
| Decision Tree      | 100%     | 1.00     | Same as above                      |
| XGBoost            | 100%     | 1.00     | Strong, but suspiciously perfect   |
| Logistic Regression| 95%      | 0.87     | Best generalization so far         |

> ⚠️ Note: The perfect accuracy in some models may indicate overfitting due to class imbalance or data leakage.

---

## ▶️ Getting Started

1. Clone this repo:
   ```bash
   git clone https://github.com/Adrshp806/fraud-detection-ml-python.git
   cd fraud-detection-ml-python
Install dependencies:

```bash
pip install -r requirements.txt
Launch the notebook:

```bash
jupyter notebook notebooks/fraud_detection_analysis.ipynb
📘 Final Report
See the report/ folder for full documentation:

CA4U_14589_ADRSH.pdf: Final submitted version

CA4U_14589_ADRSH.docx: Editable version

💬 Notes
This project is educational and for research purposes. The dataset used is publicly available on Kaggle and should be used in compliance with their terms.