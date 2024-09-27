**Advertisement Sale Prediction using Logistic Regression**
**Project Overview :**
This project focuses on predicting advertisement sales based on customer behavior data using Logistic Regression. 
The objective is to identify potential sales outcomes (buying vs. not buying) for advertisements displayed to customers, utilizing demographic and behavioral factors.

**Problem Statement:**
Given the behavioral data of existing customers, the goal is to predict whether a customer will purchase the product after viewing an advertisement.
This classification problem is solved using Logistic Regression to model the binary outcome of the purchase decision (Yes/No).

**Dataset:**
The dataset consists of customer information and their responses to advertisements. It includes features such as:
Age: Customer's age
Salary : The customer's monthly income.
Status : State of buying or not

**Methodology:**
Logistic Regression Model
Logistic Regression is chosen for this project as it is a well-suited model for binary classification problems. The process involves:

**Data Preprocessing:** Handling missing values, encoding categorical variables, and scaling numerical features.
Model Training: Using the preprocessed data to train a logistic regression model to predict the target variable (advertisement sale).
Model Evaluation: Evaluating the model using accuracy, precision, recall, and the confusion matrix.
Steps:
Exploratory Data Analysis (EDA) to understand the relationships between features and the target.
Feature Selection to identify the most relevant features.
Model Training using LogisticRegression from Scikit-learn.
Model Validation using cross-validation and confusion matrix to evaluate performance.

**Evaluation Metrics**
The performance of the model is evaluated using the following metrics:
Accuracy: Measures how often the model is correct.
Confusion Matrix: To visualize the classification performance.

**Results**
The logistic regression model achieved the following results on the test set:
Accuracy: 80%
