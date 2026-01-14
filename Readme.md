 ANN Churn Prediction Project

## 📌 Overview
This project predicts **customer churn** using an **Artificial Neural Network (ANN)**.  
Customer churn refers to customers who stop using a company’s service.  
By predicting churn in advance, businesses can take preventive actions to retain customers.

This project uses **machine learning and deep learning techniques** to analyze customer data and predict whether a customer is likely to leave or stay.

---

## ❓ Problem Statement
Customer retention is critical for business growth.  
Manually identifying customers who may churn is difficult and inefficient.

This project aims to:
- Analyze customer behavior
- Predict churn using an ANN model
- Help businesses make data-driven decisions

---

## 🧠 Model Used
- Artificial Neural Network (ANN)
- Trained using **TensorFlow / Keras**
- Binary classification (Churn / No Churn)

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries & Frameworks:**
  - NumPy
  - Pandas
  - Scikit-learn
  - TensorFlow / Keras
- **Development Tools:**
  - Jupyter Notebook
  - VS Code
  - Git & GitHub

---

## 📂 Project Structure
CHURN_PREDICTION/
│
├── app.py # Main application file
├── eda.ipynb # Exploratory Data Analysis
├── predictions.ipynb # Model prediction notebook
├── Churn_Modelling.csv # Dataset
├── model.h5 # Trained ANN model
├── scaler.pkl # Feature scaler
├── label_encoder_gender.pkl # Label encoder
├── onehot_encoder_geo.pkl # One-hot encoder
├── requirements.txt # Required dependencies
├── .gitignore # Ignored files
└── README.md # Project documentation

yaml
Copy code

---

## 📊 Dataset Information
- Dataset: Customer churn dataset
- Features include:
  - Credit score
  - Geography
  - Gender
  - Age
  - Balance
  - Number of products
  - Estimated salary
- Target variable:
  - `Exited` (1 = Churn, 0 = Not Churn)

---

## ⚙️ How the Project Works
1. Load and preprocess customer data  
2. Encode categorical features  
3. Scale numerical features  
4. Train ANN model  
5. Save trained model and encoders  
6. Predict churn for new customers  

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/spradhan33/CHURN_PREDICTION.git