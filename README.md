# 💳 Credit Scoring Model

This project uses **Machine Learning** to predict whether a loan applicant is **creditworthy** or **high-risk**, based on key financial features like income, credit score, loan amount, and more. The goal is to assist financial institutions in making smarter lending decisions.

---

## 📌 Problem Statement

Lending to the wrong customer can lead to financial loss. This model predicts the **credit risk** of an applicant using historical data, allowing institutions to assess whether a customer is **low-risk (creditworthy)** or **high-risk**.

---

## 🧠 ML Approach

- **Model Used**: `RandomForestClassifier`
- **Data Preprocessing**:
  - Missing value handling
  - Feature encoding (Label/OneHot Encoding)
  - Feature scaling (StandardScaler / MinMaxScaler)
- **Evaluation Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-score

---

## 🗂️ Dataset

The dataset contains financial features such as:
- Applicant income
- Credit score
- Loan amount
- Employment status
- Debt-to-income ratio
- Previous default history  
(*Ensure the dataset is cleaned and anonymized before use*)

---

## 🧪 Model Evaluation

The model's performance is evaluated using:
- **Accuracy** – How many predictions were correct.
- **Precision** – How many predicted creditworthy applicants were truly creditworthy.
- **Recall** – How many actual creditworthy applicants were correctly identified.
- **F1-Score** – Harmonic mean of precision and recall.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Credit-scoring-model-.git
   cd Credit-scoring-model-

