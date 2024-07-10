# Predicting Heart Attack Risk - Data Science Assignment

## Problem Statement

Develop machine learning models to predict whether a person is likely to have a heart attack based on demographic and health-related data collected in a survey by a US health organization.

## Dataset

- **File**: `US_Heart_Patients.csv`
- **Objective**: Predict heart attack risk using machine learning models.

## Steps Implemented

### 1. Load the Data

- Read `US_Heart_Patients.csv` into the program.

### 2. Exploratory Data Analysis (EDA)

- Display first 10 rows, 5-point summary, data types, handle outliers, impute missing values, calculate correlations, and visualize data distribution.

### 3. Data Preprocessing

- Impute missing values, handle outliers, and encode categorical features.

### 4. Split the Dataset

- Split into 80% training and 20% test data.

### 5. Model Preparation and Evaluation

#### Naïve Bayes Model

- Train and predict on both train and test datasets.
- Calculate F1 score for evaluation.

#### Decision Tree Model

- Train and predict on both train and test datasets.
- Calculate F1 score for evaluation.

### Model Evaluation

- Compare models based on F1 score.
- Explain the best model's confusion matrix and classification report.

