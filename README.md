# my-portfolio-Valentine
# Stroke Prediction Project

This project aims to predict the likelihood of stroke in patients based on various demographic and health-related features using machine learning models. The analysis was performed on a stroke dataset with preprocessing, exploratory data analysis, feature engineering, and model tuning to improve prediction accuracy.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Dataset](#dataset)  
- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Models](#models)  
- [Results](#results)  
- [License](#license)  

---

## Project Overview

Stroke is a critical health condition, and early prediction can save lives. This project leverages machine learning algorithms to predict stroke risk using patient data such as age, gender, hypertension, heart disease, glucose level, BMI, and smoking status.

The project includes:  
- Data preprocessing and cleaning (handling missing values, outliers, encoding categorical variables)  
- Exploratory data analysis (visualizations, correlations)  
- Feature scaling and balancing (using SMOTE for imbalanced classes)  
- Model training and evaluation with Random Forest, Logistic Regression, and Support Vector Machine  
- Hyperparameter tuning using RandomizedSearchCV for optimized model performance  

---

## Dataset

The dataset used is a transformed version of the stroke dataset named `Transformed_Stroke_Dataset_Updated_v2.csv` / `Transformed_Stroke_Dataset_Updated_2.csv`. It contains multiple features related to patient demographics and health metrics.

---

## Features

- **age**: Patient's age  
- **gender**: Patient's gender  
- **hypertension**: Whether the patient has hypertension (0 = No, 1 = Yes)  
- **heart_disease**: Whether the patient has heart disease (0 = No, 1 = Yes)  
- **avg_glucose_level**: Average glucose level in blood  
- **bmi**: Body Mass Index  
- **smoking_status**: Smoking status of the patient  
- **work_type**: Type of work  
- **Residence_type**: Residence type (Urban or Rural)  
- **stroke**: Target variable indicating stroke occurrence (0 = No, 1 = Yes)  

---

## Installation

To run this project, you'll need Python 3.x and the following packages:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn imbalanced-learn scipy

