# ANN Churn Prediction Project

## 📌 Overview
This project predicts **customer churn** using an **Artificial Neural Network (ANN)**.  
Customer churn refers to customers who stop using a company’s service.  

By predicting churn in advance, businesses can take preventive actions to improve customer retention.

This project uses **machine learning and deep learning techniques** to analyze customer data and classify customers as **Churn** or **Not Churn**.

---

## ❓ Problem Statement
Customer retention is critical for business growth.  
Manually identifying customers who may churn is difficult and inefficient.

This project aims to:
- Analyze customer behavior
- Predict customer churn using an ANN model
- Help businesses make data-driven decisions

---

## 🧠 Model Used
- Artificial Neural Network (ANN)
- Built using **TensorFlow / Keras**
- Binary classification:
  - `1` → Churn
  - `0` → Not Churn

---

## 🛠️ Tech Stack
### Programming Language
- Python

### Libraries & Frameworks
- NumPy
- Pandas
- Scikit-learn
- TensorFlow / Keras

### Development Tools
- Jupyter Notebook
- VS Code
- Git & GitHub

---

## 📂 Project Structure

```text
CHURN_PREDICTION/
├── app.py                     # Main application file
├── eda.ipynb                  # Exploratory Data Analysis
├── predictions.ipynb          # Model prediction notebook
├── Churn_Modelling.csv        # Dataset
├── model.h5                   # Trained ANN model
├── scaler.pkl                 # Feature scaler
├── label_encoder_gender.pkl   # Label encoder
├── onehot_encoder_geo.pkl     # One-hot encoder
├── requirements.txt           # Required dependencies
├── .gitignore                 # Ignored files
└── README.md                  # Project documentation
