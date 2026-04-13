# 🍕 Pizza Sales & Ingredient Analysis Application

A machine learning and forecasting project that analyzes pizza ingredient and sales data.  
It predicts demand, evaluates classification models, and provides insights for restaurant inventory optimization.

---

## 📌 Project Overview
This project uses **Random Forest, Logistic Regression, and Decision Tree classifiers** for classification tasks, and an **ARIMA time series model** for forecasting pizza demand.  
The pipeline includes preprocessing, feature encoding, model training, evaluation, and demand forecasting.

---

## ✨ Features
- Preprocessing pipeline for missing values, duplicates, and categorical encoding  
- Exploratory Data Analysis (EDA) with histograms, Q-Q plots, and Shapiro-Wilk test  
- Classification models with evaluation metrics (accuracy, precision, recall, F1)  
- Confusion matrices and classification reports for each model  
- ARIMA forecasting for daily pizza demand  
- Visualizations including pie charts for weekly demand distribution  

---

## 🧠 Machine Learning Components

The project uses the following components:

| Component | Purpose |
|-----------|---------|
| `preprocess.py` | Cleans data, handles missing values, encodes categorical features |
| `train_models.py` | Trains Random Forest, Logistic Regression, Decision Tree models |
| `forecast.py` | ARIMA forecasting for pizza demand |
| `metrics_summary.csv` | Stores evaluation metrics for all models |
| `confusion_matrix.png` | Confusion matrix visualization |
| `feature_importance.png` | Feature importance visualization |
| `forecast_pie.png` | Forecasted weekly pizza demand distribution |

---

## 🛠️ Tech Stack
- Python 3.x  
- Pandas / NumPy  
- Scikit‑learn  
- Statsmodels  
- Matplotlib  
- Streamlit (optional for UI)

---

---
### Model Evaluation
| Model              | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Random Forest      | 0.87     | 0.86      | 0.85   | 0.85     |
| Logistic Regression| 0.74     | 0.72      | 0.71   | 0.71     |
| Decision Tree      | 0.80     | 0.79      | 0.78   | 0.78     |


---
## Future Pridiction for Pizza
<img width="1920" height="1080" alt="Screenshot (92)" src="https://github.com/user-attachments/assets/0edb67a4-d1ff-49bd-99b6-e20c1b968c4a" />
<img width="1920" height="1080" alt="Screenshot (93)" src="https://github.com/user-attachments/assets/b2a42f03-edf0-4350-9aa7-6f2cf43600db" />
<img width="1920" height="1080" alt="Screenshot (94)" src="https://github.com/user-attachments/assets/cc32a6a7-691e-4fbf-a517-f73a02e50cd3" />
---
## Future Prediction for Ingredient
<img width="1920" height="1080" alt="Screenshot (95)" src="https://github.com/user-attachments/assets/f02bcd5f-d5c5-4b2d-a01d-60288b6d0fd6" />





