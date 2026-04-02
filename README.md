# 🌊 FloodSight: Real-Time Flood Risk Classifier & Route Analysis

## 📌 Overview
FloodSight is an AI-powered web application that predicts flood risk using real-time weather data and provides intelligent route analysis with interactive mapping.

AI-Powered Flood Risk Prediction System using Real-Time Weather Data.

---

## 🎯 Problem Statement
Flood risk systems are often:
- Static and outdated ❌  
- Not location-specific ❌  
- Lacking real-time insights ❌  

FloodSight solves this by:
- Using real-time weather data  
- Predicting flood risk using ML  
- Providing route-based safety recommendations  

---

## 🧠 Features
- Real-time flood prediction  
- Logistic Regression model  
- Interactive route mapping  
- Risk classification (Low / High)  

---

## 📥 Example Input
- Temperature: 30°C  
- Humidity: 80%  
- Rainfall: 50 mm  

## 📤 Output
- Flood Risk: High 🔴  

---

## 📊 Model Evaluation
Confusion Matrix:
[[9, 1],
 [3, 127]]

Accuracy: 97%  
Balanced Accuracy: ~94%  
Precision: 99.2%  
Recall: 97.7%  

---

## 🤔 Why Logistic Regression?
- Simple and efficient for binary classification  
- Works well on small datasets  
- Easy to understand and interpret  

---

## 🗺️ Features - Mapping
- Direct route  
- Highway route  
- Alternate route  

---

## 📸 Screenshots

### 🔹 Flood Risk Prediction UI
![Prediction UI](images/prediction.png)
![Prediction UI 2](images/prediction1.png)

### 🔹 Route Map Visualization
![Map UI](images/map.png)
![Map UI 2](images/map1.png)
![Map UI 3](images/map2.png)
---

## 📂 Project Structure
FloodSight/
├── app.py  
├── model.pkl  
├── thane_flood_data.csv  
├── requirements.txt  
├── images/  
└── README.md  

---

## 🛠️ Tech Stack
- Python  
- Streamlit  
- scikit-learn  
- pandas  
- numpy  
- folium  

---

## 📦 Requirements
- Python 3.x  
- Streamlit  
- scikit-learn  
- pandas  
- numpy  
- folium  

---

## 🚀 Installation
1. Download or copy the project folder  
2. Open in VS Code  
3. Install dependencies:

pip install -r requirements.txt  

---

## ▶️ Run the App
streamlit run app.py  

---

## ⚠️ Limitations
- Model depends on dataset quality  
- API failure may affect results  
- Limited dataset  

---

## 👨‍💻 Author
Aashish Lande 

---

## 🏆 Conclusion
FloodSight demonstrates how Machine Learning + Real-Time Data can solve real-world flood problems.
