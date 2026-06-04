# Adult Income Prediction using Machine Learning

## Overview

This project predicts whether a person earns more than $50K per year using demographic and employment-related data.

It is a classic binary classification problem and is useful for understanding real-world structured data analysis.

---

## Problem Statement

Income prediction is important for many data analysis and machine learning applications.

The challenge is to classify individuals into two categories:
- income less than or equal to $50K
- income greater than $50K

---

## Solution

This notebook preprocesses the Adult Income dataset, encodes categorical features, trains multiple classification models, and compares their performance.

---

## Dataset

The dataset contains 48,842 rows and 15 columns.

### Input Features
- age
- workclass
- fnlwgt
- education
- educational-num
- marital-status
- occupation
- relationship
- race
- gender
- capital-gain
- capital-loss
- hours-per-week
- native-country

### Target Variable
- Income class

---

## Workflow / Working

1. Load the dataset in Google Colab.
2. Inspect the shape, columns, and data types.
3. Check for missing values.
4. Perform exploratory data analysis.
5. Encode categorical variables using one-hot encoding.
6. Split the dataset into training and testing sets.
7. Train multiple classification models.
8. Evaluate the results using classification metrics.
9. Compare the model performance.
10. Use the trained model for prediction.

---

## Models Used

- Logistic Regression
- Random Forest Classifier

---

## Key Results

- Logistic Regression Accuracy: 0.8521
- Random Forest Accuracy: 0.8605

The Random Forest model performed slightly better than Logistic Regression in this notebook.

---

## Features Covered in the Notebook

- Data loading and inspection
- Missing-value check
- EDA visualizations
- One-hot encoding
- Train-test split
- Model comparison
- Confusion matrix
- Classification report
- Class prediction analysis

---

## Why This Project Matters

This project is a practical example of binary classification on census-style data. It is a good demonstration of how machine learning can be applied to socio-economic prediction problems.

---

## Screenshots

The folder contains screenshots showing:
- dataset preview
- preprocessing
- EDA plots
- model results
- classification output

---

## How to Run

1. Open the notebook in Google Colab.
2. Run the notebook cell by cell.
3. Check the preprocessing and evaluation steps.
4. Review the accuracy and classification report.

---

## Learning Outcomes

Through this project, I learned:
- data encoding
- classification workflow
- model comparison
- evaluation metrics
- working with real census data

---

## Future Improvements

- Try additional models such as XGBoost or SVM
- Handle class imbalance more carefully
- Tune hyperparameters
- Save the final model
- Build a dashboard for prediction

---

## Author

Pranav Mahesh Palled
