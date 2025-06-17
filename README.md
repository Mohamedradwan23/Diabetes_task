# Diabetes Prediction Dataset

## Overview
This repository contains a dataset and exploratory data analysis (EDA) for diabetes prediction. The dataset includes several medical predictor variables and one target variable (`Outcome`), indicating whether the patient has diabetes (1) or not (0).

## Dataset Description
The dataset consists of 60 patient records with the following features:

| Feature | Description | Type |
|---------|-------------|------|
| Pregnancies | Number of times pregnant | Integer |
| Glucose | Plasma glucose concentration (2 hours in an oral glucose tolerance test) | Integer |
| BloodPressure | Diastolic blood pressure (mm Hg) | Integer |
| SkinThickness | Triceps skin fold thickness (mm) | Integer |
| Insulin | 2-Hour serum insulin (mu U/ml) | Integer |
| BMI | Body mass index (weight in kg/(height in m)^2) | Float |
| DiabetesPedigreeFunction | Diabetes pedigree function | Float |
| Age | Age in years | Integer |
| Outcome | Class variable (0 - no diabetes, 1 - diabetes) | Binary |

## Key Findings from EDA
1. **Class Distribution**: The dataset is somewhat balanced between diabetic and non-diabetic cases.
2. **Important Correlations**:
   - Glucose level has the strongest positive correlation with diabetes outcome
   - BMI and Age show moderate positive correlations
3. **Visual Insights**:
   - Diabetic patients tend to have higher glucose levels
   - Higher BMI is associated with higher diabetes risk
   - Diabetes is more common in older individuals
