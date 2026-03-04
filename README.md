# Obesity Level Prediction using Machine Learning

## Overview
This project uses machine learning techniques to predict obesity levels based on lifestyle habits and physical attributes.

The goal is to support early identification of obesity risk and enable data-driven health interventions.

## Dataset
- Source: UCI Machine Learning Repository
- Records: 2,111
- Features: 17
- Target: Obesity Level (multi-class)

## Methods

### Data Preprocessing
- No missing values
- One-hot encoding for categorical variables
- Label encoding for target variable
- Train-test split (70/30)
- Feature scaling for KNN

### Models Used
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier

### Model Tuning
- KNN: Optimal k = 5
- Decision Tree: Optimal max_depth = 9

## Results
- KNN Accuracy: ~77%
- Decision Tree performed better overall
- Macro F1 used as primary evaluation metric

## Key Insights
- Weight and height are the strongest predictors
- Middle classes (e.g., normal weight) are harder to classify
- Decision Tree handles mixed data types better

## Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Business Impact
- Can be used to build early obesity screening tools
- Supports targeted health interventions
