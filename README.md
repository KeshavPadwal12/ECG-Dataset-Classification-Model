# ECG-Dataset-Classification-Model
This repository contains a deep learning model developed for classifying health conditions based on Electrocardiogram (ECG) data. The project aims to demonstrate the application of neural networks in medical diagnostics, offering a robust solution for automated preliminary screening.

1. Introduction
Cardiovascular diseases remain a leading cause of mortality worldwide. Early and accurate detection of heart conditions is crucial for effective treatment and improved patient outcomes. Electrocardiograms (ECGs) are a non-invasive and widely used tool for assessing cardiac function. This project leverages a deep learning approach to analyze ECG-related physiological and lifestyle parameters, classifying individuals into predefined health categories. The model utilizes a multi-layer perceptron (MLP) built with Keras and TensorFlow, demonstrating high accuracy in predicting target outcomes.

2. Data Description
The dataset used in this project is an "ECG-Dataset.csv" file, which contains 21 features and 333 entries. Each entry represents an individual's health record with various physiological and lifestyle attributes relevant to cardiovascular health. The columns are:

1. age: Age of the individual.

2. sex: Gender of the individual (likely binary: 0 for female, 1 for male).

3. smoker: Indicates if the individual is a smoker (binary: 0 or 1).

4. years_of_smoking: Number of years the individual has been smoking.

5. LDL_cholesterol: Low-Density Lipoprotein (LDL) cholesterol level.

6. chest_pain_type: Type of chest pain experienced (categorical).

7. height: Height of the individual in centimeters.

8. weight: Weight of the individual in kilograms.

9. familyhist: Family history of heart disease (binary: 0 or 1).

10. activity: Level of physical activity (likely categorical or numerical).

11. lifestyle: Lifestyle habits (likely categorical or numerical).

12. cardiac intervention: Indicates if the individual has undergone cardiac intervention (binary: 0 or 1).

13. heart_rate: Resting heart rate.

14. diabets: Indicates if the individual has diabetes (binary: 0 or 1).

15. blood_pressure_sys: Systolic blood pressure.

16. blood_pressure_dias: Diastolic blood pressure.

17. hypertention: Indicates if the individual has hypertension (binary: 0 or 1).

18. Interventricular_septal_end_diastole: Interventricular septal end-diastole measurement (likely related to echocardiogram).

19. ecg_pattern: ECG pattern type (categorical).

20. Q_wave: Presence of Q-wave (binary: 0 or 1).

21. target: The target variable for classification (e.g., presence or absence of a specific heart condition, or severity level).

Data Overview:
The dataset dimensions are (333, 21), indicating 333 samples and 21 features (including the target variable).


