# Credit Card Fraud Detection Prediction Readme

## Overview
This repository contains a project for predicting credit card fraud based on transaction data. The dataset has undergone various preprocessing steps, including duplicate removal, missing value check, outlier treatment, data scaling and balancing the data. The predictive model used for this project is Logistic Regression.

## Contents
**Credit Card Fraud Detection.ipynb**: Jupyter Notebook containing the entire codebase for the project.
## Steps
### 1. Data Preprocessing
- **Duplicate Removal:** Duplicate records were identified and removed to ensure the dataset's integrity.
- **Missing Values Check:** No missing values were present in the dataset.
- **Outlier Treatment:** Outliers were treated using the capping and flooring method to enhance model performance.

### 2. Data Balancing
To address the imbalance in the dataset (492 fraud, 284,807 total), downsampling was performed to create a balanced dataset with 984 rows (492 fraud, 492 non-fraud).

### 3. Data Scaling
The data was scaled using the robust scaler to standardize the features and mitigate the impact of outliers.

### 4. Data Partition (Logistic Regression)
The dataset was split into training and testing sets, with logistic regression used as the predictive model.

### Model Evaluation
#### Train Report
- Precision: Class 0 (0.99), Class 1 (0.92)
- Recall: Class 0 (0.92), Class 1 (0.99)
- F1-Score: Class 0 (0.96), Class 1 (0.95)
- Accuracy: 0.96

#### Test Report
- Precision: Class 0 (0.99), Class 1 (0.89)
- Recall: Class 0 (0.90), Class 1 (0.99)
- F1-Score: Class 0 (0.94), Class 1 (0.94)
- Accuracy: 0.94

### Conclusion
The Logistic Regression model demonstrated strong performance on both the training and testing sets. The balanced dataset and preprocessing steps contribute to the model's effectiveness in identifying credit card fraud. The project provides a foundation for credit card fraud detection using machine learning techniques.
