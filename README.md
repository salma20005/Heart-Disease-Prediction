# Heart Disease Prediction

## Project Overview

This project aims to predict the presence of heart disease using machine learning techniques. The dataset used is the UCI Heart Disease dataset, which contains medical information collected from patients.

## Objectives

* Perform exploratory data analysis (EDA).
* Clean and preprocess the data.
* Analyze feature correlations.
* Build and evaluate multiple machine learning models.
* Compare model performance using different evaluation metrics.

## Dataset

* Number of samples: 303
* Target variable: `target`
* Task: Binary Classification (Heart Disease / No Heart Disease)

## Exploratory Data Analysis

* Checked for missing values.
* Checked and removed duplicate records.
* Investigated outliers.
* Visualized target distribution.
* Analyzed feature correlations using a heatmap.

## Data Preprocessing

* Removed duplicate rows.
* Split the dataset into training and testing sets.
* Applied feature scaling using StandardScaler.

## Models Used

1. Logistic Regression
2. Support Vector Machine (Linear SVM)
3. K-Nearest Neighbors (KNN)
4. Random Forest

## Evaluation Metrics

* Accuracy Score
* Classification Report
* Confusion Matrix
* ROC Curve
* ROC-AUC Score

## Results

 Multiple models were compared to identify the most suitable approach for heart disease prediction. Linear SVM & KNN achieved the highest performance.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Future Improvements

* Cross Validation
* Hyperparameter Tuning using GridSearchCV
* Pipeline Implementation
* Feature Importance Analysis
* Model Deployment with Streamlit
