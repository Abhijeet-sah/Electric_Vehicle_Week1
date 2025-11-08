# ⚡ Electric Vehicle Battery Health Prediction using Machine Learning

## 📘 Project Overview
This project focuses on predicting the **Battery State of Health (SoH)** and **Remaining Useful Life (RUL)** of **Electric Vehicles (EVs)** using **Machine Learning (ML)** techniques.  
The health of EV batteries degrades over time due to repeated charging and discharging cycles, temperature, and other environmental factors.  
By predicting battery health, manufacturers and users can:
- Prevent sudden failures,  
- Plan predictive maintenance,  
- Increase safety, and  
- Extend battery lifespan.

---

## 🎯 Objective
The main objective of this project is to develop a **data-driven model** capable of:
1. Predicting the **State of Health (SoH)** of EV batteries.  
2. Estimating the **Remaining Useful Life (RUL)** before performance drops below 80%.  
3. Providing insights into the key factors influencing battery degradation.  
4. Building an interpretable, efficient, and reproducible **ML pipeline** for deployment.

---

## 🧩 Problem Statement
Electric vehicle batteries degrade with usage and time.  
Traditional physics-based models are limited because:
- They need extensive lab calibration.
- They fail under varying driving and climate conditions.

Hence, this project proposes a **Machine Learning-based solution** that learns battery degradation patterns directly from historical data and predicts future performance with high accuracy.

---

## ⚙️ Methodology / Workflow
The project follows this workflow:

```mermaid
graph LR
A[Battery Dataset] --> B[Data Preprocessing]
B --> C[Feature Engineering]
C --> D[Model Training]
D --> E[Evaluation & Validation]
E --> F[Visualization & Dashboard]
