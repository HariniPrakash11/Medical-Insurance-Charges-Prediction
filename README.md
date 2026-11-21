# Medical Insurance Charges Prediction Using Machine Learning

## Project Overview
This project focuses on developing a machine learning model to predict medical insurance charges based on individual characteristics such as age, sex, BMI, smoking habits, number of children, and region.

The project explores the factors associated with medical insurance costs and compares different regression models to identify the model with the best prediction performance.

## Problem Statement
Medical insurance charges vary among individuals depending on factors such as age, BMI, smoking habits, and other personal characteristics.

This project aims to develop a machine learning model that analyzes these factors and predicts medical insurance charges for individuals.

## Project Objectives
- Analyze medical insurance data.
- Identify factors influencing insurance charges.
- Develop regression models to predict insurance charges.
- Evaluate model performance using regression metrics.
- Generate predictions for new individuals.

## Dataset Description
**Dataset:** Medical Cost Personal Dataset

**Target Variable:** Charges

**Features:**
- Age
- Sex
- BMI
- Children
- Smoker
- Region

The dataset contains personal and demographic information used to predict individual medical insurance charges.

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow
1. Data exploration
2. Exploratory Data Analysis (EDA)
3. Data preprocessing
4. Train-test splitting
5. Encoding categorical variables
6. Feature scaling
7. Model development
8. Model evaluation
9. Prediction using the selected model

## Machine Learning Algorithms
The following regression algorithms were implemented:

- Linear Regression
- Decision Tree Regression
- Random Forest Regression

## Model Evaluation
The models were evaluated using:
- R-squared (R²)
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

### Key Findings
- Smoking status showed a significant association with medical insurance charges.
- Age showed a positive relationship with insurance charges.
- Random Forest Regression achieved the best overall performance among the three models.

**Best Model:** Random Forest Regression

**R-squared Score:** Approximately 0.805

**MAE:** Approximately 2,655.21

## Conclusion
This project demonstrates the application of machine learning regression algorithms to predict medical insurance charges. Among the three models developed, Random Forest Regression achieved the best prediction performance.

The project provided practical experience in data exploration, preprocessing, regression modelling, model evaluation, and prediction in the insurance domain.

## Limitations
- Linear Regression produced a few negative predictions, even though insurance charges cannot be negative.
- Model performance depends on the quality and characteristics of the available dataset.
- The models were trained using a limited set of customer features. Including additional relevant factors may improve prediction performance.