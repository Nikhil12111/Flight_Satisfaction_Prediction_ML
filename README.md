# ✈️ Flight Satisfaction Prediction — Machine Learning Project  
Predicting airline passenger satisfaction using machine learning and a deployed Streamlit web app.

---

## 📌 Overview

This project analyzes airline passenger data to predict whether a customer is **Satisfied** or **Neutral/Dissatisfied** using machine learning.  
It includes:

- Data preprocessing  
- Feature engineering  
- Model training (XGBoost)  
- Streamlit web application  
- Model deployment-ready code  

---

## 📁 Project Structure

flight_satisfaction_prediction_ml/
│
├── app.py # Streamlit web application
├── models/
│ └── model.pkl # Trained XGBoost model
├── data/
│ └── train.csv # Training dataset
├── README.md # Project documentation
└── requirements.txt # Python dependencies


---

## 🎯 Objective

Airlines must understand customer experience factors that drive satisfaction.  
This system predicts **Customer Satisfaction** based on:

- Personal info  
- Travel type  
- Flight delays  
- In-flight service ratings  

---

## 📊 Dataset

The dataset contains:

### **Customer Information**
- Age  
- Gender  
- Customer Type  
- Type of Travel  
- Class  

### **Flight Information**
- Flight Distance  
- Departure Delay  
- Arrival Delay  

### **Service Ratings (0–5 scale)**  
14 columns including:

- WiFi Service  
- Gate Location  
- Seat Comfort  
- Inflight Entertainment  
- Food & Drink  
- Cleanliness  
- Online Boarding  
- and more…

---

## ⚙️ Feature Engineering

Two engineered features were added:

1️⃣ **Total Delay** = Departure Delay + Arrival Delay  
2️⃣ **Average Service Rating** = Mean of all service ratings  

---

## 🤖 Model Used

### ✔ XGBoost Classifier  
Perfect for tabular classification and gives high accuracy.

Saved as:

models/model.pkl


---

## 🖥️ Streamlit Web App

Users enter their flight & service details.  
The app outputs:

- **Satisfied 😀**  
or  
- **Neutral / Dissatisfied 😐**

Run locally:



---

## 🚀 Technologies Used

- Python  
- Pandas  
- NumPy  
- XGBoost  
- Streamlit  
- Matplotlib  
- Scikit-Learn  

---

## 🏁 Results

Strong classification accuracy using XGBoost with label encoding + feature engineering.  

---

## 🔮 Future Improvements

- Deploy to Streamlit Cloud  
- Add SHAP visual explanations  
- Hyperparameter tuning with Optuna  
- Mobile UI improvements

---

## 🤝 Contributions

PRs and suggestions are welcome!

---

## 📜 License

MIT License.
