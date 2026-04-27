# 📊 Simple Linear Regression: Gender → Final_Score

## 📌 Overview

This project analyzes the relationship between **Gender** and **Final Score** using a Simple Linear Regression model.

---

## 🎯 Objective

* Predict Final Score based on Gender
* Analyze whether gender has any impact on academic performance

---

## 🧾 Feature & Target

* **Input Feature (X):** Gender
* **Target Variable (y):** Final_Score

---

## 🔧 Data Preprocessing

* Missing values handled using median (numeric) and mode (categorical)
* Duplicate rows removed
* Gender encoded into numerical form using LabelEncoder
* Feature scaling applied using StandardScaler

---

## ⚙️ Model Training

* Algorithm: Linear Regression
* Train/Test Split: 80% training, 20% testing

---

## 📈 Model Evaluation

* Metric: R² Score

---

## 📊 Visualization

* Scatter plot + regression line used

📌 Insight:

* Gender shows **weak or minimal impact** on final scores compared to other features

---

## 💾 Model Saving

* Model and scaler saved using joblib

---

## 🧠 Conclusion

* Gender alone is not a strong predictor of academic performance
* Other factors like study habits and attendance are more influential

---
