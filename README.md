
# Hospital Emergency Wait Time Risk Prediction and Analysis 🚑📊
Dashboard Screen Short:
<img width="1532" height="852" alt="image" src="https://github.com/user-attachments/assets/61a2b492-54e3-495a-8a1b-d0f524f3f7c0" />
Structure:
Hospital-Emergency-Wait-Time-Risk-Prediction/
│
├── data/
│   └── cleaned_hospital_data.csv
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_wait_time_risk_model.ipynb
│
├── powerbi/
│   └── hospital_emergency_dashboard.pbix
│
├── README.md
└── requirements.txt


# Hospital Emergency Wait Time Risk Prediction 🚑📊

## Project Overview
This project analyzes emergency ward patient data and builds a **predictive machine learning framework** to identify patients at **high risk of experiencing long wait times**.  

The goal is to support **hospital operations teams** with proactive, data-driven decision-making rather than reactive reporting.

---

## Problem Statement
Emergency departments often face congestion, leading to long patient wait times and reduced satisfaction.  
Traditional dashboards show historical performance but **cannot predict future delays**.

This project answers the question:

> Can we predict whether a patient will experience a long wait time at the moment of arrival?

---

## Dataset Description
The dataset contains **9,216 patient records** with the following key attributes:

- Patient demographics (Age, Gender, Race)
- Admission details
- Department referral
- Waiting time
- Satisfaction score
- Date and time of arrival

Data spans **2023–2024**.

---

## Dashboard Insights (Power BI)
A Power BI dashboard was developed to explore:
- Patient volume trends
- Average waiting time (35.26 minutes)
- Admission rate (~50%)
- Satisfaction levels (avg rating = 5.0)
- Treatment within 30 minutes (59.32%)

These insights motivated the need for **predictive modeling**.

---

## Machine Learning Objective
### Target Variable
