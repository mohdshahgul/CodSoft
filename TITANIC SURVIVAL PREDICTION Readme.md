# Overview
This repository contains a Titanic survival prediction project where the aim to predict the survival status of passengers based on various features. The dataset has undergone several preprocessing steps, including the removal of duplicates, treatment of missing values, and elimination of irrelevant columns. The predictive models employed include Logistic Regression, Random Forest, Gradient Boosting, XGBoost, and AdaBoost.

## Contents
TITANIC SURVIVAL PREDICTION.ipynb: Jupyter Notebook containing the entire codebase for the project.

## Steps
### 1. Data Preprocessing
Duplicate Removal: Duplicate records were identified and removed to ensure the dataset's integrity.
Missing Values Treatment: Various techniques were used to handle missing values, ensuring data completeness.
Irrelevant Column Removal: Columns that were deemed irrelevant for prediction were dropped.
### 2. Label Encoding
Categorical variables were encoded using label encoding to convert them into a format suitable for machine learning models.
### 3. Data Splitting
The dataset was split into training and testing sets to evaluate model performance. The split ratio used was 80% for training and 20% for testing.
### 4. Model Building
The following machine learning models were employed:

##### a. Logistic Regression
Accuracy Score (Training): 78.33%
Accuracy Score (Testing): 76.49%
Recall Score (Training): 82.88%
Recall Score (Testing): 82.43%
Precision Score (Training): 52.38%
Precision Score (Testing): 54.95%
##### b. Random Forest
Accuracy Score (Training): 87.16%
Accuracy Score (Testing): 80.97%
Recall Score (Training): 87.94%
Recall Score (Testing): 81.25%
Precision Score (Training): 75.76%
Precision Score (Testing): 70.27%
##### c. Gradient Boosting
Accuracy Score (Training): 92.30%
Accuracy Score (Testing): 80.60%
Recall Score (Training): 94.20%
Recall Score (Testing): 79.80%
Precision Score (Training): 84.42%
Precision Score (Testing): 71.17%
##### d. XGBoost
Accuracy Score (Training): 82.50%
Accuracy Score (Testing): 80.60%
Recall Score (Training): 78.50%
Recall Score (Testing): 79.21%
Precision Score (Training): 72.73%
Precision Score (Testing): 72.07%

## Conclusion
The models were evaluated based on accuracy, recall, and precision scores. Further tuning and optimization can be performed to enhance model performance. 
The Gradient Boosting model demonstrated the highest accuracy on the training set, while Random Forest performed well on the testing set.
