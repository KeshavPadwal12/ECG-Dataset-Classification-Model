# ECG-Dataset-Classification-Model
This repository contains a deep learning model developed for classifying health conditions based on Electrocardiogram (ECG) data. The project aims to demonstrate the application of neural networks in medical diagnostics, offering a robust solution for automated preliminary screening.

1. Introduction
Cardiovascular diseases remain a leading cause of mortality worldwide. Early and accurate detection of heart conditions is crucial for effective treatment and improved patient outcomes. Electrocardiograms (ECGs) are a non-invasive and widely used tool for assessing cardiac function. This project leverages a deep learning approach to analyze ECG-related physiological and lifestyle parameters, classifying individuals into predefined health categories. The model utilizes a multi-layer perceptron (MLP) built with Keras and TensorFlow, demonstrating high accuracy in predicting target outcomes.

2. Data Description
The dataset used in this project is an "ECG-Dataset.csv" file, which contains 21 features and 333 entries. Each entry represents an individual's health record with various physiological and lifestyle attributes relevant to cardiovascular health. The columns are:

age: Age of the individual.

sex: Gender of the individual (likely binary: 0 for female, 1 for male).

smoker: Indicates if the individual is a smoker (binary: 0 or 1).

years_of_smoking: Number of years the individual has been smoking.

LDL_cholesterol: Low-Density Lipoprotein (LDL) cholesterol level.

chest_pain_type: Type of chest pain experienced (categorical).

height: Height of the individual in centimeters.

weight: Weight of the individual in kilograms.

familyhist: Family history of heart disease (binary: 0 or 1).

activity: Level of physical activity (likely categorical or numerical).

lifestyle: Lifestyle habits (likely categorical or numerical).

cardiac intervention: Indicates if the individual has undergone cardiac intervention (binary: 0 or 1).

heart_rate: Resting heart rate.

diabets: Indicates if the individual has diabetes (binary: 0 or 1).

blood_pressure_sys: Systolic blood pressure.

blood_pressure_dias: Diastolic blood pressure.

hypertention: Indicates if the individual has hypertension (binary: 0 or 1).

Interventricular_septal_end_diastole: Interventricular septal end-diastole measurement (likely related to echocardiogram).

ecg_pattern: ECG pattern type (categorical).

Q_wave: Presence of Q-wave (binary: 0 or 1).

target: The target variable for classification (e.g., presence or absence of a specific heart condition, or severity level).

Data Overview:
The dataset dimensions are (333, 21), indicating 333 samples and 21 features (including the target variable).
