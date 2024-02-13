# Iris Flower Readme
## Overview
This repository contains a project for predicting the species of Iris flowers based on various features. The dataset has undergone several preprocessing steps, including duplicate removal, outlier treatment, label encoding, and data partition. The predictive model employed for this project is Random Forest.

## Contents
Iris flower.ipynb: Jupyter Notebook containing the entire codebase for the project.

## Steps
### 1. Data Preprocessing
Duplicate Removal: Duplicate records were identified and removed to ensure the dataset's integrity.
Missing Values Check: No missing values were present in the dataset.
Outlier Treatment: Outliers were identified and treated to enhance model performance.
### 2. Label Encoding
Categorical variables were encoded using label encoding to convert them into a format suitable for machine learning models.
### 3. Data Partition
The dataset was split into training and testing sets to evaluate model performance. The split ratio used was 70% for training and 30% for testing.
### 4. Model Building - Random Forest
The Random Forest model was employed for this project, achieving good results on both the training and testing sets.

### Model Evaluation
##### Train Report
- Precision: Class 0 (1.00), Class 1 (0.76), Class 2 (1.00)
- Recall: Class 0 (0.86), Class 1 (1.00), Class 2 (0.89)
- F1-Score: Class 0 (0.93), Class 1 (0.87), Class 2 (0.94)
- Accuracy: 91%
##### Test Report
- Precision: Class 0 (1.00), Class 1 (0.75), Class 2 (0.94)
- Recall: Class 0 (0.89), Class 1 (0.90), Class 2 (0.94)
- F1-Score: Class 0 (0.94), Class 1 (0.82), Class 2 (0.94)
- Accuracy: 91%

## Conclusion
The Random Forest model demonstrated good performance on both the training and testing sets. Users are encouraged to explore additional features, hyperparameter tuning, and other advanced techniques to further improve the model. The project provides a foundation for understanding and predicting the species of Iris flowers based on the given features.
