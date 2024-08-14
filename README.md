# **Disease Prediction Model**

## **Project Overview**

This project involves developing a machine learning model to predict the presence of a disease based on patient data. The goal is to build a model that achieves high performance, evaluated using the ROC-AUC score. The project includes data preprocessing, model training, and prediction generation.

## **Datasets**

- **Training Dataset:** `Disease_train.csv`
  - Contains patient features and the target variable for training and validation.
  - Features: `patient_id`, `feature_1` to `feature_n`, `diagnosis` (0 = no disease, 1 = disease).

- **Test Dataset:** `Disease_test.csv`
  - Contains patient features without the target variable, used for final evaluation.

## **Objectives**

1. **Data Preprocessing:**
   - Load the training dataset.
   - Handle missing values and perform feature engineering and scaling.

2. **Model Training:**
   - Split the training dataset into training and validation subsets.
   - Train machine learning models (e.g., Logistic Regression, Random Forest, Gradient Boosting).
   - Optimize model hyperparameters for best performance.

3. **Prediction:**
   - Load the test dataset.
   - Generate predictions and save them in a CSV file named `student_<ID>_predictions.csv`, where `<ID>` is your unique student ID. The CSV file should contain columns: `patient_id`, `prediction`.
