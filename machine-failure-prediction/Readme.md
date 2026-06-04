# Machine Failure Prediction using Machine Learning

## Overview

Predictive maintenance is one of the most useful applications of machine learning in industry. Unexpected machine failures can cause downtime, increase repair costs, and reduce productivity.

This project predicts whether a machine is likely to fail based on operational and sensor-related features. It demonstrates a complete machine learning workflow from data exploration to model evaluation and sample prediction.

---

## Problem Statement

Industrial machines generate continuous data through sensors and operating parameters.

The challenge is to use this data to predict failures before they happen so that maintenance can be planned in advance.

This helps reduce:
- sudden breakdowns
- downtime
- maintenance cost
- production loss

---

## Solution

This notebook uses supervised machine learning to classify whether a machine will fail or not.

The workflow includes:
1. Loading the dataset
2. Exploring the data
3. Checking missing values
4. Visualizing patterns
5. Training multiple classification models
6. Comparing their performance
7. Making a sample prediction

---

## Dataset

The dataset contains 944 rows and 10 columns.

### Input Features
- footfall
- tempMode
- AQ
- USS
- CS
- VOC
- RP
- IP
- Temperature

### Target Variable
- Machine failure status

---

## Workflow / Working

1. Load the dataset in Google Colab.
2. Inspect the shape, columns, and data types.
3. Check for missing values.
4. Perform exploratory data analysis using histograms and count plots.
5. Prepare the dataset for machine learning.
6. Split the data into training and testing sets.
7. Train multiple classification models.
8. Evaluate each model using accuracy, confusion matrix, and classification report.
9. Use the best model for sample prediction.

---

## Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## Key Results

- Logistic Regression Accuracy: 0.8677
- Decision Tree Accuracy: 0.8042
- Random Forest Accuracy: 0.8783

The Random Forest model performed the best in this notebook.

---

## Features Covered in the Notebook

- Data loading and inspection
- Missing-value analysis
- EDA with histograms and count plots
- Train-test split
- Model comparison
- Confusion matrix
- Classification report
- Feature importance analysis
- Sample prediction

---

## Why This Project Matters

This project shows how machine learning can support predictive maintenance in real-world industrial environments. It is a practical example of how structured data can be used to prevent failures before they occur.

---

## Screenshots

The folder contains screenshots showing:
- dataset inspection
- data preprocessing
- plots and analysis
- model training
- evaluation output
- final prediction

---

## How to Run

1. Open the notebook in Google Colab.
2. Upload or connect the dataset.
3. Run the cells from top to bottom.
4. Review the graphs, model output, and prediction result.
5. Test the notebook with your own input values if needed.

---

## Learning Outcomes

Through this project, I learned:
- classification workflow
- data preprocessing
- exploratory data analysis
- model comparison
- evaluation metrics
- predictive maintenance basics

---

## Future Improvements

- Try XGBoost or SVM
- Tune hyperparameters
- Save the trained model
- Add a Streamlit dashboard
- Build a real-time predictive maintenance system

---

## Author

Pranav Mahesh Palled
