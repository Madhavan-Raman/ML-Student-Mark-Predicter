# 📘 ML Student Marks Predictor

A simple **Machine Learning + Flask API** that predicts student marks based on the number of study hours.  
The model is trained using **Linear Regression** and served as a REST API for real-time predictions.

---

## 🚀 Features
- 🔹 Predict marks based on study hours  
- 🔹 Flask REST API with JSON input/output  
- 🔹 Model trained & saved with `scikit-learn` + `joblib`  
- 🔹 Error handling for invalid or missing inputs  

---

## 🛠️ Tech Stack
- Python 3
- Flask
- Scikit-learn
- Joblib

---

## 📌 API Endpoints

### `GET /`
- Returns a welcome message  
✅ Example:
```json
"Welcome to Student Marks Prediction API!"
