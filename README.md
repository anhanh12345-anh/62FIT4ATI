# 62FIT4ATI
## Diabetes Risk Prediction Using Machine Learning & MLP
This project focuses on predicting diabetes risk using the CDC BRFSS dataset. Multiple machine learning models are implemented and compared, with a primary emphasis on a Multilayer Perceptron (MLP) neural network optimized for medical relevance, especially Recall for at-risk patients.

---

## Problem Definition
Task: Binary classification
Objective: Predict whether a person is at risk of diabetes
Classes:
0 – No Diabetes
1 – At Risk (Prediabetes + Diabetes)
Due to the strong class imbalance in the dataset, the project prioritizes Recall and ROC-AUC rather than Accuracy alone.
ls

---

## Dataset Description
Source: CDC BRFSS (Behavioral Risk Factor Surveillance System)
Shape: (269,131 samples, 22 columns)
Target Variable: Diabetes_binary
Input Features: 21 features
**Input Features (21)**
**Demographics:**
Age (13 levels)
Sex (Male/Female)
Education (1–6)
Income (1–8)
**Health Conditions:**
HighBP
HighChol
CholCheck
BMI
Stroke
HeartDiseaseorAttack
**Lifestyle / Habits:**
Smoker
PhysActivity
Fruits
Veggies
HvyAlcoholConsump
**General Health:**
GenHlth (1–5)
MentHlth
PhysHlth
DiffWalk
**Healthcare Access:**
AnyHealthcare
NoDocbcCost

---
## Models Implemented

The following models are trained and evaluated:
Logistic Regression (Baseline)
Random Forest Classifier
Multilayer Perceptron (MLP) – Main focus

---
## Visualizations Included
Target class distribution (before & after binarization)
Correlation heatmap
Feature histograms (BMI, Age, GenHlth)
Training & validation loss curves (MLP)
Training & validation accuracy curves (MLP)
Confusion matrix
ROC curve
Precision–Recall vs Threshold curve

---

## Repository Contents

| File | Description |
|---|---|
| `62FIT4ATI_Group 16_Topic 1.ipynb` | Main Jupyter notebook containing preprocessing, modeling, evaluation, and inference |
| `62FIT4ATI_Group 16_Topic 1_REPORT.docx` | Project report |
| `mlp_diabetes_model.h5` | Trained MLP model |
| `scaler.pkl` | StandardScaler used for preprocessing |
| `feature_names.pkl` |  |
| `requirements.txt` | Project dependencies |
| `README.md` | Project documentation |

---

## Setup Guide

### Clone the Repository
```bash
git clone 
