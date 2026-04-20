# Spatial-Temporal Analysis of Theft Crime Risk in Urban Communities using Deep Learning

## 📌 Overview
This project is an intelligent **crime risk prediction system** designed to analyze theft crime patterns in urban communities using **Deep Learning** and **Machine Learning** techniques.  

The system predicts crime risk levels by learning both:

- **Temporal patterns** (when crimes happen)
- **Spatial relationships** (where crimes happen)

The project integrates:

- **LSTM (Long Short-Term Memory)** – for time-series crime trends  
- **ST-GCN (Spatial-Temporal Graph Convolutional Network)** – for spatial dependency modeling  
- **GBDT (Gradient Boosting Decision Trees)** – for final risk prediction refinement  

The final output is displayed in an **interactive dashboard** showing crime risk categories and insights. :contentReference[oaicite:0]{index=0}

---

## 🎯 Objectives

- Predict theft crime risk in urban regions
- Identify high-risk locations
- Detect peak crime time periods
- Support smart policing and resource allocation
- Provide visual analytics dashboard

---

## 🧠 Technologies Used

| Category | Tools / Libraries |
|---------|------------------|
| Language | Python |
| ML / DL | TensorFlow, Keras, Scikit-learn |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Plotly |
| Model Types | LSTM, ST-GCN, GBDT |
| Dataset | Chicago Crimes Dataset |

---

## 📂 Project Structure

```bash
Crime-Risk-Prediction/
│── CrimeRiskPrediction.ipynb
│── crime_risk_dashboard.html
│── requirements.txt
│── run.bat
│── model/
│── Dataset/
│── README.md
