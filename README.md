# Breast Cancer Detection Using Machine Learning

## Overview
This project focuses on detecting breast cancer using machine learning techniques. The objective is to analyze and preprocess the **Kaggle Wisconsin Breast Cancer Dataset**, train various machine learning models, and predict whether a given breast cancer tumor is malignant or benign, which can aid in early diagnosis and medical decision-making. The **Random Forest** algorithm was identified as the most effective model for accurate diagnosis prediction.

## Features
- Comprehensive data preprocessing
- Implementation and evaluation of key machine learning algorithms:
  - Naive Bayes
  - Logistic Regression
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - **Random Forest** (used for final diagnosis prediction)
- Model performance comparison based on accuracy and ROC-AUC metrics
- Visualization of results to aid decision-making

## Dataset
The project uses the **Kaggle Wisconsin Breast Cancer Dataset**, which contains diagnostic data derived from breast cancer cell nuclei. The dataset provides features for malignancy detection, enabling accurate and automated classification.

Dataset link: [Wisconsin Breast Cancer Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

## Workflow
1. **Data Preprocessing:**
   - Detection and handling of outliers
   - Conversion of categorical values to numeric values
   - Splitting data into training and testing sets

2. **Model Training:**
   - Train and evaluate multiple machine learning models:
     - Naive Bayes
     - Logistic Regression
     - Support Vector Machine (SVM)
     - K-Nearest Neighbors (KNN)
     - **Random Forest**

3. **Prediction Using Random Forest:**
   - Random Forest was selected as the final model for diagnosis prediction based on its superior accuracy and ROC-AUC scores.
   - It effectively handles the dataset's complexity, capturing feature interactions for reliable predictions.

4. **Performance Evaluation:**
   - Custom accuracy metrics (e.g., confusion matrix components)
   - Comparison of models using accuracy and ROC-AUC scores
   - Visualization of model performances for insights

## Results
The **Random Forest** algorithm consistently outperformed other models, demonstrating high diagnostic accuracy and robust performance. This makes it the ideal choice for breast cancer detection in this project.

