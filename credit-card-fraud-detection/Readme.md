# Credit Card Fraud Detection using Machine Learning

## Overview

Credit card fraud detection is one of the most important applications of machine learning in finance.

This project detects suspicious transactions using supervised learning and compares multiple models on a highly imbalanced dataset.

---

## Problem Statement

Financial transactions happen at a massive scale, and fraudulent activity must be detected quickly and accurately.

The challenge is to classify each transaction as:
- normal
- fraud

---

## Solution

This notebook loads the dataset, analyzes class imbalance, trains classification models, and evaluates them using standard metrics.

---

## Dataset

The dataset contains 284,807 rows and 31 columns.

### Input Features
- Time
- Amount
- Anonymous features V1 to V28

### Target Variable
- Fraud or Normal transaction

---

## Workflow / Working

1. Load the dataset in Google Colab.
2. Inspect the shape, columns, and data types.
3. Check for missing values.
4. Perform exploratory data analysis.
5. Visualize the class imbalance.
6. Separate features and target.
7. Split the dataset into training and testing sets.
8. Train classification models.
9. Evaluate the results using classification metrics.
10. Make a sample transaction prediction.

---

## Models Used

- Logistic Regression
- Random Forest Classifier

---

## Key Results

- Logistic Regression Accuracy: 0.9989
- Random Forest Accuracy: 0.9996

The Random Forest model performed slightly better in this notebook.

---

## Features Covered in the Notebook

- Data loading and inspection
- Missing-value check
- Class imbalance visualization
- Feature separation
- Train-test split
- Model comparison
- Confusion matrix
- Classification report
- Sample transaction prediction

---

## Why This Project Matters

Fraud detection is a high-impact machine learning use case. Even small improvements can help prevent financial losses and improve transaction safety.

---

## Screenshots

The folder contains screenshots showing:
- dataset analysis
- imbalance visualization
- training process
- evaluation output
- sample prediction

---

## How to Run

1. Open the notebook in Google Colab.
2. Run each cell in order.
3. Review the class distribution and model results.
4. Test the model using sample transaction values.

---

## Learning Outcomes

Through this project, I learned:
- imbalanced classification handling
- fraud detection workflow
- model evaluation
- predictive analytics
- real-world financial ML use cases

---

## Future Improvements

- Try anomaly detection models
- Use SMOTE or other balancing techniques
- Tune thresholds for fraud detection
- Add model interpretability
- Build a transaction monitoring dashboard

---

## Author

Pranav Mahesh Palled
