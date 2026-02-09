# 💳 Online Payment Fraud Detection – ML + Flask API

A machine learning based system that detects fraudulent online transactions and exposes the prediction as a REST API using Flask.

---

## 📌 Project Overview
Online payment systems face increasing fraud risk.  
This project builds an end-to-end pipeline that:
1. Trains a machine learning model on transaction data  
2. Saves the trained model  
3. Serves predictions through a Flask backend API  

This simulates how ML models are used in real backend systems.

---

## 🚀 Features
- Data preprocessing using Pandas & NumPy
- Machine learning model training using Scikit-learn
- Model serialization using Pickle
- REST API for real-time fraud prediction
- Simple backend deployment using Flask

---

## 🧠 Machine Learning Workflow
1. Load transaction dataset  
2. Split into train & test data  
3. Train Logistic Regression model  
4. Save trained model (`model.pkl`)  
5. Use Flask API to predict fraud in real time  

---

## 🛠 Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Flask  

---

## 📁 Project Structure
fraud-detection-ml/
│
├── train_model.py # Train ML model
├── app.py # Flask API for prediction
├── requirements.txt
├── sample_transactions.csv
└── model.pkl


---

## ⚙️ How to Run the Project

### 1️⃣ Install dependencies
pip install -r requirements.txt


### 2️⃣ Train the model
python train_model.py


### 3️⃣ Run Flask API
python app.py


API runs at:
http://127.0.0.1:5000/


---

## 🔮 Future Improvements
- Deploy API on AWS / Cloud
- Add real-time streaming data
- Improve accuracy using ensemble models
- Add frontend dashboard

---

## 👩‍💻 Author
**Narupalle Siva Nandini**