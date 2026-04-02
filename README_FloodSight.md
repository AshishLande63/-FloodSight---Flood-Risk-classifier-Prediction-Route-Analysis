# 🌊 FloodSight - Flood Risk classifier Prediction & Route Analysis

## 📌 Overview
FloodSight is an AI-powered web application that predicts flood risk using real-time weather data and provides intelligent route analysis with interactive mapping.

The system combines Machine Learning (Logistic Regression), real-time APIs, and geospatial visualization to help users make safer travel decisions during flood-prone conditions.

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

### 🤖 AI Flood Risk Prediction
- Model: Logistic Regression (scikit-learn)
- Input Features:
  - Temperature  
  - Humidity  
  - Rainfall  
  - Pressure  
  - Wind Speed  
  - Tide Level  

- Output:
  - 🟢 Low Risk  
  - 🔴 High Risk  

---

### 🌦️ Real-Time Weather Integration
- Weather data from OpenWeatherMap  
- Location via OpenStreetMap  

---

### 🗺️ Interactive Route Mapping
- Built with Folium + Streamlit
- Provides:
  - Direct route  
  - Highway route  
  - Alternate route  

- Risk Visualization:
  - 🟢 Low Risk  
  - 🟡 Moderate Risk  
  - 🔴 High Risk  

---

## 📊 Model Performance
- Accuracy: 97%  
- Balanced Accuracy: ~94%  
- Precision: 99.2%  
- Recall: 97.7%  

---

## ⚙️ How It Works

User Input → Weather Data → Feature Engineering → Logistic Model → Prediction → Map Output

---

## 📂 Project Structure

FloodSight/
├── app.py  
├── model.pkl  
├── thane_flood_data.csv  
├── requirements.txt  
└── README.md  

---

## 🛠️ Tech Stack
- Python  
- Streamlit  
- Scikit-learn  
- Pandas & NumPy  
- Folium  
- Requests  

---

## 🚀 Installation

1. Download or copy the project folder to your system  

2. Open the project folder in VS Code or any IDE  

3. Open terminal and install required dependencies:

pip install -r requirements.txt

---

## ▶️ Run the App

streamlit run app.py  

---

## 🔑 API Setup
Get API key from OpenWeatherMap and replace in app.py

---

## 🏆 Conclusion
FloodSight shows how Machine Learning + Real-Time Data + Mapping can solve real-world flood risk problems.
