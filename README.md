# Fraud-Detection-in-Credit-Card-Transactions
# 💳 Credit Card Fraud Detection App

This project is a Streamlit-based web application that detects fraudulent credit card transactions using a machine learning model trained on the popular Kaggle dataset. It includes features for file upload, manual transaction input, model evaluation, and visualization.

## 🚀 Live App

👉 [Click here to try the app](https://sample-6hddxzvngpvwfxzp2gr3kv.streamlit.app/)  

---

## 📦 Features

- 🔐 Password-protected access
- 📤 Upload CSV files for batch prediction
- ✍️ Enter single transaction manually
- 📈 Feature importance visualization (XGBoost)
- 📊 Confusion matrix for model evaluation
- 📥 Download predictions as CSV
- ✅ Real-time fraud detection with probability scores

---

## 🧠 Machine Learning Model

- **Algorithm**: XGBoost Classifier
- **Techniques Used**:
  - Data scaling (`Amount` feature)
  - Anomaly detection (Isolation Forest, LOF)
  - Undersampling for class balance
  - Evaluation with ROC curve, AUC, confusion matrix

---

## 📁 Project Structure

├── app.py # Streamlit web app

├── xgb_fraud_model.pkl # Trained model (binary format)

├── requirements.txt # List of required packages

└── creditcard.csv (optional) # Original dataset for testing

## 🛠️ Installation & Local Run

**1. Clone the repo**:
   
     git clone https://github.com/AnuSwathi02/Sample.git
     cd Sample

**2. Install dependencies**:

     pip install -r requirements.txt

**3.Run the app**:

    streamlit run app.py

## 🔐 Access
**Default password**: mysecret (It can be changed in app.py)

## 📊 Dataset

**Source**: Kaggle - Credit Card Fraud Detection

**Highly imbalanced** (fraud cases ≈ 0.17%)

**Features**: PCA-transformed V1–V28 + Amount, Time, Class



    
