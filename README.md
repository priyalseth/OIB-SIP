#  Fraud Detection using Logistic Regression

This project demonstrates how to build a **Fraud Detection System** using a **Logistic Regression model** on credit card transaction data. The goal is to accurately classify transactions as fraudulent or legitimate using a supervised learning approach.

---

## Project Overview

-  Dataset: [Credit Card Fraud Detection (Kaggle)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
-  Algorithm Used: Logistic Regression
-  Key Concepts: Class imbalance handling, feature preprocessing, evaluation metrics
-  Tools: Python, Pandas, Scikit-learn, Matplotlib, Seaborn

---

## Problem Statement

Credit card fraud is a significant issue in the financial industry. The dataset contains transactions made by European cardholders in September 2013. Out of 284,807 transactions, only 492 are fraud — making it a highly **imbalanced classification problem**.

---

## Project Structure

| Section | Description |
|--------|-------------|
| `Import Libraries` | Load necessary Python libraries |
| `Load and Explore Data` | Read the CSV, check class distribution |
| `Preprocessing` | Handle missing data, balance the dataset |
| `Train-Test Split` | Split the balanced dataset |
| `Model Training` | Train logistic regression |
| `Model Evaluation` | Confusion matrix, classification report |
| `ROC Curve` | Visualize performance (AUC = 0.98) |
| `Save Model` | Export trained model using `joblib` |

---

## Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **AUC (Area Under Curve)**

> The trained model achieved an **AUC of 0.98**, showing excellent capability to distinguish fraud from non-fraud transactions.

---

##  Technologies Used

- Python 3.10+
- Google Colab
- Scikit-learn
- Matplotlib / Seaborn
- Pandas / Numpy
- Joblib (for saving models)

---

## Future Improvements

-  Use **SMOTE** for oversampling instead of undersampling
-  Try advanced models like **Random Forest**, **XGBoost**, or **LightGBM**
-  Deploy as a **REST API** using Flask
-  Monitor real-time fraud with **cloud deployment (AWS/GCP)**

---

##  Dataset Source

This project uses the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud), which contains:

- 284,807 transactions
- 492 frauds (0.172%)
- Features: V1–V28 (PCA components), `Time`, `Amount`, `Class`

---

## Contact

If you'd like to connect, feel free to reach out:


- GitHub: [Priyal Seth](https://github.com/priyalseth)
- LinkedIn: [Priyal Seth](https://www.linkedin.com/in/priyal-seth-2493302a2/)
- Email: sethshreya1999@gmail.com

---



###  End of Project

Thanks for checking out this project! ⭐ Star the repo if you found it helpful.
