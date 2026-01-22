# Advertisement Sale Prediction Using Logistic Regression

## Project Overview

This project focuses on predicting advertisement sales outcomes based on customer demographic and behavioral data using Logistic Regression. The objective is to determine whether a customer is likely to purchase a product after viewing an advertisement. This binary classification model helps businesses evaluate advertisement effectiveness and target the right customer segments.

The project demonstrates a complete machine learning workflow, including data preprocessing, exploratory analysis, model training, and performance evaluation.

---

## Problem Statement

Given historical customer data, the goal is to predict whether a customer will purchase a product after being exposed to an advertisement. The target variable represents a binary outcome (purchase or no purchase), making Logistic Regression an appropriate and interpretable modeling approach.

---

## Dataset Description

The dataset contains customer-related attributes and their responses to advertisements.

### Features

* **Age:** Customer’s age
* **Salary:** Customer’s monthly income
* **Status:** Purchase decision (target variable: buy / not buy)

---

## Tools and Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## Methodology

### 1. Data Preprocessing

* Checked and handled missing values
* Encoded categorical variables
* Scaled numerical features
* Prepared the final dataset for model input

### 2. Exploratory Data Analysis

* Analyzed feature distributions
* Studied relationships between independent variables and the target
* Identified relevant features for modeling

### 3. Model Development

* Algorithm: Logistic Regression
* Implemented using `LogisticRegression` from Scikit-learn
* Trained the model on preprocessed training data

### 4. Model Evaluation

The model performance was evaluated using:

* Accuracy score
* Confusion matrix
* Precision and recall

Cross-validation was applied to ensure model reliability.

---

## Evaluation Metrics

* **Accuracy:** Measures overall correctness of predictions
* **Confusion Matrix:** Visualizes true positives, true negatives, false positives, and false negatives
* **Precision and Recall:** Evaluate the quality of positive predictions

---

## Results

The trained Logistic Regression model achieved an accuracy of approximately **80%** on the test dataset, demonstrating its effectiveness in predicting customer purchase behavior from advertisement exposure.

---

## Applications

* Advertisement performance analysis
* Customer conversion prediction
* Marketing campaign optimization
* Sales forecasting support
* Business decision-making systems

---

## Conclusion

This project demonstrates how Logistic Regression can be effectively applied to predict advertisement sales outcomes. By combining preprocessing, exploratory analysis, and evaluation techniques, the model provides meaningful insights into customer purchase behavior and supports data-driven marketing strategies.

---

## Future Enhancements

* Include additional behavioral and engagement features
* Apply feature engineering to improve predictive performance
* Compare Logistic Regression with models such as Random Forest and SVM
* Deploy the model as a web-based prediction service


