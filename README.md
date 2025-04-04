💳 RiskLens – AI-Powered Credit Risk Scoring Model

An end-to-end **machine learning pipeline** to predict the likelihood of loan default using real-world financial data. 
This project combines **traditional ML** with **explainable AI (XAI)** and **LLM-powered reasoning** to simulate real-world credit risk analysis systems.

---

## 🚀 Overview

This project answers one question:  
**Can we predict if a loan applicant is likely to default and explain the reasoning behind that prediction clearly and responsibly?**

To solve this, I built a complete pipeline using:

- ✅ **Random Forest** for robust classification
- ✅ **SMOTE** to handle class imbalance
- ✅ **SHAP** to explain model decisions (global + local)
- ✅ **Manual rule-based logic** to simulate business knowledge
- ✅ **GPT-2 (Hugging Face)** to auto-generate natural language insights

---

## 🧠 Techniques & Skills Used

| ------------Area-----------| Techniques / Tools |
|----------------------------|--------------------|
| **ML Modeling**            | Random Forest Classifier (scikit-learn) |
| **Class Imbalance**        | SMOTE (Synthetic Minority Oversampling Technique) |
| **Feature Engineering**    | StandardScaler, Label Encoding |
| **Explainability (XAI)**   | SHAP summary plots, SHAP TreeExplainer |
| **Model Evaluation**       | Classification Report, Confusion Matrix, ROC AUC |
| **AI Reasoning**           | Hugging Face `transformers`, GPT-2 |
| **Tools**                  | Jupyter Notebook, Pandas, Matplotlib, Seaborn |
| **Other**                  | Git, GitHub, Joblib, Imbalanced-learn |

---

## 📊 Results Summary

- ✅ Model trained on **30,000 real loan applications**
- ✅ Achieved **99% ROC AUC score**
- ✅ Clear explanations using **SHAP + rule-based logic**
- ✅ Natural language summaries powered by **GPT-2**

---

## Data Set Source

- https://www.kaggle.com/datasets/beatafaron/loan-credit-risk-and-population-stability

---

## 🧱 Project Structure

```bash
RiskLens-AI-Powered-Credit-Risk-Scoring/
├── Credit_Risk_Scoring_Model.ipynb       # Main notebook with explanations
├── credit_risk_rf_model.pkl             # Trained ML model
│── scaler.pkl                            # Preprocessing scaler
├── README.md                             # You're reading it
├── requirements.txt                      # All Python dependencies
└── .gitignore
