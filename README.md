# Height Predictor Using Body Measurements

This project uses machine learning to predict a person's total height based on various body measurements such as chest width, waist size, leg length and more. It's built end-to-end using a real-world dataset and includes full preprocessing, training, evaluation and manual testing.

---

## Problem Statement

> **Goal:** Predict the `TotalHeight` of an individual using other body measurements.

This is a **regression problem**, and the best-performing model in this project is a **Random Forest Regressor**.

---

## Dataset

- Source: [Body Measurements Dataset](https://www.kaggle.com/datasets/saurabhshahane/body-measurements-dataset)
- Total Samples: ~700
- Features Used:
  - Gender, Age, Head Circumference, Shoulder Width, Chest Width, Belly, Waist, Hips, Arm Length, Shoulder to Waist, Waist to Knee, Leg Length
- Target:
  - `TotalHeight` (in inch)

---

## Workflow Summary

1. **Data Loading & Cleaning**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Engineering & Preprocessing**
4. **Model Training**
5. **Model Evaluation (R², MAE, RMSE)**
6. **Hyperparameter Tuning**
7. **Model Saving & Real-time Testing**
8. **(Optional) Deployment-ready Code**

---

## Best Model Results

| Metric         | Value         |
|----------------|---------------|
| R² Score       | **0.719**     |
| MAE            | **4.25 inch**   |
| RMSE           | **42.42 inch**  |
| Model          | Random Forest |

---

