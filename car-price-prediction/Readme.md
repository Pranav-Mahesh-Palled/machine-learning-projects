# Car Price Prediction using Machine Learning

## Overview

Car price prediction is a useful machine learning regression problem that helps estimate the selling price of a vehicle based on its specifications and features.

This project shows a complete regression pipeline from data preprocessing to model evaluation and final prediction.

---

## Problem Statement

Used car prices depend on many factors such as age, fuel type, transmission, engine capacity, and vehicle condition.

The challenge is to build a model that can estimate a car’s selling price more accurately than manual guessing.

---

## Solution

This notebook preprocesses the car dataset, converts categorical variables into usable form, trains regression models, and compares their performance.

---

## Dataset

The dataset contains 205 rows and 26 columns.

### Input Features
Vehicle-related attributes such as:
- year
- fuel type
- transmission
- engine-related values
- car condition-related features

### Target Variable
- Selling price

---

## Workflow / Working

1. Load the dataset in Google Colab.
2. Inspect the shape, columns, and data types.
3. Check for missing values.
4. Perform exploratory data analysis.
5. Encode categorical values.
6. Prepare features and target variable.
7. Split the data into training and testing sets.
8. Train regression models.
9. Evaluate the model using regression metrics.
10. Compare predicted prices with actual prices.

---

## Models Used

- Linear Regression
- Random Forest Regressor

---

## Key Results

- Random Forest R² Score: 0.9593600963881497

The Random Forest model gave strong performance and was the most effective model in this notebook.

---

## Features Covered in the Notebook

- Data loading and inspection
- Missing-value check
- EDA visualizations
- Categorical encoding
- Feature preparation
- Regression model training
- R² evaluation
- Prediction vs actual plot

---

## Why This Project Matters

Car price prediction is a real-world regression use case. It shows how machine learning can estimate continuous values using structured data.

---

## Screenshots

The folder contains screenshots showing:
- dataset exploration
- preprocessing steps
- model training
- regression results
- prediction comparison plot

---

## How to Run

1. Open the notebook in Google Colab.
2. Upload or connect the dataset.
3. Run the cells in sequence.
4. Review the plots and evaluation score.
5. Test the model with sample values.

---

## Learning Outcomes

Through this project, I learned:
- regression modeling
- categorical encoding
- data preprocessing
- evaluation with R² score
- prediction comparison

---

## Future Improvements

- Try XGBoost or Gradient Boosting
- Tune hyperparameters
- Add feature selection
- Create a price prediction web app
- Save the trained model for reuse

---

## Author

Pranav Mahesh Palled
