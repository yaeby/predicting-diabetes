# Diabetes Prediction Model

This repository contains a machine learning model designed to predict whether a patient has diabetes based on several medical parameters. The model uses the **K-Nearest Neighbors (KNN)** algorithm to classify patients based on their medical history and physical measurements.

## Dataset

The dataset used for this project is publicly available and contains various medical details such as glucose levels, blood pressure, BMI, age, and more. The target variable is whether the patient has diabetes or not.

You can find and download the dataset from the following link:
[Diabetes Dataset](https://www.kaggle.com/datasets/nanditapore/healthcare-diabetes/data)

## Features

The dataset includes the following features:
- **Id**: Unique identifier for each data entry.
- **Pregnancies**: Number of times the patient has been pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body Mass Index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age (years)
- **Outcome**: 1 if the patient has diabetes, 0 otherwise (Target)

## Model Overview

The model uses the **K-Nearest Neighbors (KNN)** algorithm to predict diabetes. It was optimized using **GridSearchCV** to find the best hyperparameters. The model was trained and tested using a split dataset, with feature scaling applied for better performance.

### Key Steps:
1. **Data Preprocessing**: Handle missing values and scale features using `StandardScaler`.
2. **Data Visualization**: Visualize feature correlations, distributions, and relationships.
3. **Model Tuning**: Hyperparameter tuning using `GridSearchCV`.
4. **Evaluation**: Confusion matrix, accuracy, and ROC curve.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction-model.git
