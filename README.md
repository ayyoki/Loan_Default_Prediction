# Loan Default Prediction

## Overview
The primary objective of this project is to develop a binary classification model that predicts loan defaults using bank data. Specifically, the model will forecast defaults occurring 30 days after the loan is issued.

**Remarks**: The dataset is small, but we achieve good results even with this dataset.

## Development Environment
- **Platform**: Google Collaboratory

## Libraries Used

### Data Pre-Processing and Analysis
- NumPy
- pandas
- Matplotlib
- Seaborn
- scikit-learn (sklearn)
- missingno

### Model Training
- XGBoost

### Evaluation Metrics
- scikit-learn (sklearn.metrics)
- Yellowbrick

## Introduction to the Dataset
- **Source**: Provided by a real bank (name withheld)
- **Description**: Each row in the dataset represents a record of obtaining credit. Note: All columns in the dataset are in Ukrainian.
- **Size**: 
  - Train dataset: 528 rows and 14 columns
  - Test dataset: 132 rows

## Project Steps
1. Fill in the missing values
2. Feature Engineering
3. Outlier handling
4. Column encoding
5. Exploratory Data Analysis (EDA)
6. Feature selection (RFECV and feature importance)
7. Class balancing using SMOTE method
8. Model building and selection of optimal parameters (using the Optuna library)

## Results and Metrics
The model performance is summarized by the following metrics:
- **Accuracy**: 0.976
- **Class 0 Recall**: 0.97
- **Class 1 Recall**: 1.0
