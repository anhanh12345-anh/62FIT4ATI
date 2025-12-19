# 62FIT4ATI
# Diabetes Risk Prediction Using MLP

This repository presents a **diabetes risk prediction system** based on a **Feedforward Neural Network (Multi-Layer Perceptron – MLP)** trained on the **CDC BRFSS dataset**.  
The project addresses **class imbalance** using **SMOTE** and prioritizes **high Recall**, which is crucial for medical decision-support systems.

---

## Problem Overview

- **Task**: Binary classification  
  - `0` – Healthy  
  - `1` – At Risk (Prediabetes + Diabetes)
- **Dataset size**: 269,131 samples
- **Class imbalance**: ~84% Healthy, ~16% At Risk
- **Goal**: Minimize false negatives by improving Recall for at-risk individuals

---

## Features

- **21 input features**, grouped as:
  - **Demographics**: Age, Sex, Education, Income
  - **Health Conditions**: HighBP, HighChol, CholCheck, BMI, Stroke, HeartDiseaseorAttack
  - **Lifestyle Factors**: Smoker, Physical Activity, Alcohol Consumption, Fruits, Veggies
  - **General Health**: GenHlth, MentHlth, PhysHlth, DiffWalk
  - **Healthcare Access**: AnyHealthcare, NoDocbcCost
- **Binary output**: Diabetes risk prediction

---

## Repository Contents

| File | Description |
|---|---|
| `62FIT4ATI_Group_19_Topic_1.ipynb` | Main Jupyter notebook containing preprocessing, modeling, evaluation, and inference |
| `report.docx` | Project report |
| `diabetes_risk_model.joblib` | Trained MLP model |
| `scaler.joblib` | StandardScaler used for preprocessing |
| `requirements.txt` | Project dependencies |
| `README.md` | Project documentation |

---

## Setup Guide

### 1. Clone the Repository
```bash
git clone https://github.com/Primo23-w/62FIT4ATI_Group-19_Topic-1.git
cd 62FIT4ATI_Group_19_Topic_1
