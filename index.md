# 🧬 Renal Lithiasis Risk Prediction  
### Clinical Machine Learning for Early Kidney Stone Risk Stratification

---

## 🩺 Clinical Motivation

Kidney stone disease affects millions of patients worldwide and is associated with:
- recurrent emergency visits  
- severe pain episodes  
- long-term renal complications  
- high healthcare costs  

Early identification of patients at higher risk enables:
- preventive interventions  
- lifestyle and dietary recommendations  
- optimized follow-up  
- reduced recurrence and complications  

This project develops a **machine learning model** to support clinicians in **early risk stratification** using routinely collected clinical variables.

---

## 📊 Project Overview

This work includes:
- structured clinical data preprocessing
- exploratory data analysis
- clinically guided feature engineering
- model development and evaluation
- interpretability and clinical insight generation 

The goal is to build a **transparent, reproducible, and clinically meaningful model** that can support decision-making in real-world settings.

---

## 🧪 Dataset

The dataset includes:
- demographic variables  
- laboratory results  
- clinical history  
- other relevant clinical features

Data preprocessing steps include: 
- handling missing values
- detecting and managing outliers
- encoding categorical variables
- scaling or transforming variables when appropriate  

---

## 🤖 Modeling Approach 

A supervised learning approach is used to predict the **risk of renal lithiasis** based on clinical features. 

Several algorithms were evaluated:
- Logistic Regression  
- Random Forest  

The final selection was based on:
- discrimination (ROC-AUC)  
- calibration  
- interpretability  
- clinical plausibility  

Cross-validation was performed to ensure robustness and generalizability.

---

## 📈 Performance Summary

Key metrics evaluated:
- ROC-AUC  
- Precision–Recall  
- Sensitivity / Specificity trade-offs  
- Calibration curves  

The model demonstrates strong predictive performance and clinically coherent behavior across subgroups.

--- 

## 📈 Evaluation 

The model is evaluated using: 
- discrimination metrics
- calibration assessment
- clinically relevant thresholds and trade‑offs

Emphasis is placed on: 
- robustness
- generalizability
- interpretability for clinicians 

---

## 🔍 Interpretability

To ensure clinical trust and transparency, the project includes:
- feature importance analysis  
- partial dependence plots  

These tools help clinicians understand **why** the model makes certain predictions.

---

## ⚠️ Limitations

- Single-center dataset  
- Potential selection bias  
- Limited imaging variables  
- Requires external validation before deployment  

---

## 📁 Project Structure

- **README.md** — Executive and technical summary  
- **notebooks/** — EDA, modeling, interpretability workflows  
- **src/** — Modular, reproducible code  
- **reports/** — Technical and clinical documentation  
- **requirements.txt** — Environment reproducibility  

---

## 🔗 Useful Links

- 👉 [Project Repository](https://github.com/PatriCT240/renal_litiasis_risk)  
- 👉 [Technical Report](https://github.com/PatriCT240/renal_litiasis_risk/tree/main/reports)
- 👉 [Modeling Notebook](https://github.com/PatriCT240/renal_litiasis_risk/tree/main/notebooks)

---

_Last updated: January 2026_
