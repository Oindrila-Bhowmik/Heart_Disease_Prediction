# ❤️ Heart Disease Prediction using Machine Learning

## Overview

This project focuses on predicting the presence of heart disease using Machine Learning techniques. Multiple classification algorithms were developed, compared, and evaluated to identify the most effective model for heart disease prediction based on clinical attributes.

The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and feature importance analysis.

---

## Problem Statement

Heart disease is one of the leading causes of death worldwide. Early prediction can help healthcare professionals identify high-risk patients and support timely medical intervention.

The objective of this project is to develop a machine learning model that can accurately predict whether a patient has heart disease based on clinical parameters.

---

## Objectives

- Build machine learning models for heart disease prediction.
- Compare multiple classification algorithms.
- Evaluate models using Accuracy, F1-Score, and ROC-AUC.
- Identify the best-performing model.
- Analyze important clinical features influencing prediction.

---

## Dataset

The project uses the **Heart Disease Dataset** (`heart.csv`) containing patient clinical information such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- ST Depression
- Slope
- Number of Major Vessels
- Thalassemia
- Target (Heart Disease)

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Machine Learning Models

The following models were implemented and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

---

## Evaluation Metrics

Models were evaluated using:

- Accuracy
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report
- ROC Curve

---

## Results

Among all the implemented models, **Random Forest Classifier** achieved the best overall performance for heart disease prediction.

Feature importance analysis showed that **Chest Pain Type (cp)** is one of the most significant predictors, followed by other clinically relevant cardiovascular features.

---

## Project Workflow

1. Import libraries
2. Load dataset
3. Data exploration and preprocessing
4. Train-test split
5. Feature scaling
6. Model training
7. Model evaluation
8. Performance comparison
9. Feature importance analysis
10. Conclusion

---

## Repository Structure

```
Heart_Disease_Prediction/
│
├── Heart_Disease_Project_Final.ipynb
├── heart.csv
└── README.md
```

---

## Conclusion

This project demonstrates how machine learning can assist in the early prediction of heart disease by analyzing patient clinical data. Comparing multiple classification algorithms showed that the Random Forest model provides the strongest predictive performance and can serve as a useful decision-support tool in healthcare applications.

---
