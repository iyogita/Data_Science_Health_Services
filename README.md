# Predicting Heart Attack Risk - Data Science Assignment

## Problem Statement

The healthcare industry is increasingly investing in intelligent systems to enhance service efficiency. This project aims to develop a machine learning model to predict the likelihood of a heart attack based on data from a survey conducted by a US health organization.

## Dataset

- **File**: `US_Heart_Patients.csv`
- **Description**: Contains information on individuals aged 30 to 80, including demographic and health parameters.
- **Objective**: Predict heart attack risk using machine learning models.

## Steps Implemented

### 1. Load the Data

- Read the `US_Heart_Patients.csv` file into the program.

### 2. Exploratory Data Analysis (EDA)

- **First 10 Rows**: Display the first 10 rows of the dataset.
- **5-Point Summary**: Provide statistical summary metrics (min, 25%, median, 75%, max).
- **Data Types**: Print information about the columns and their data types.
- **Outliers**: Identify and handle outliers using the Interquartile Range (IQR) method.
- **Missing Values**: Identify and impute missing values.
- **Correlation**: Calculate and visualize correlation between variables.
- **Data Distribution**: Visualize data distribution using histograms and box plots.

### 3. Data Preprocessing

- Impute missing values using mean imputation.
- Handle outliers using the capping method.
- Encode categorical features using Label Encoding.

### 4. Split the Dataset

- Split the data into 80% training and 20% testing sets.

### 5. Model Preparation and Evaluation

#### Naïve Bayes Model

- Train the Naïve Bayes model on the training data.
- Predict outputs for both training and testing datasets.
- Evaluate performance using classification reports, confusion matrix, and F1 score.

#### Decision Tree Model

- Train the Decision Tree model on the training data.
- Predict outputs for both training and testing datasets.
- Evaluate performance using classification reports, confusion matrix, and F1 score.

### Model Comparison and Evaluation

- Compare models based on F1 score.
- Select the best model and explain its confusion matrix and classification report.

## Installation

1. Clone the repository.
2. Install required packages using `pip install` command along with required packages.
3. Upload the `US_Heart_Patients.csv` file into the working directory.

## Usage

1. Run the notebook or script to execute the data analysis and model training.
2. Follow the steps implemented to replicate the results.

## Results

- The model with the highest F1 score was selected as the best model.
- Detailed evaluation metrics, including confusion matrix and classification report, are provided for the best model.

## Contributor

- Yogita Singh
