# Customer Churn Prediction & Retention Dashboard

## 📌 Project Overview
This project predicts customer churn (whether a customer will leave a service) and provides insights into *why* they are at risk, along with recommended retention actions.  
It also includes:
- A **machine learning model** for churn prediction.
- A **REST API (FastAPI)** for real-time scoring.
- A **business dashboard (Streamlit)** for exploring churn risks.
- Optional **MLOps features** like experiment tracking and monitoring.

## 🚀 Tech Stack
- Python (scikit-learn, XGBoost, pandas, numpy)
- SHAP (explainability)
- FastAPI (REST API)
- Streamlit (dashboard)
- Docker + Google Cloud Run (deployment)

## 📂 Repo Structure
churn-ml/
├── data/ # datasets (ignored in Git)
├── notebooks/ # EDA and experiments
├── src/ # ML training, inference, utils
├── model/ # saved model artifacts
├── api/ # FastAPI app
├── app/ # Streamlit dashboard
├── tests/ # pytest unit tests
├── README.md
├── requirements.txt
├── .gitignore