# Stroke Prediction Model

## Overview

This project aims to build a machine learning model to predict the likelihood of stroke in individuals based on various health and demographic features. The model is trained on a dataset containing information such as age, gender, hypertension, heart disease, and more. The goal is to provide early detection and intervention to reduce the risk and impact of strokes.

## Features

- **Machine Learning Model**: Utilizes algorithms such as logistic regression, decision trees, and random forests.
- **Data Preprocessing**: Includes handling missing values, encoding categorical variables, and feature scaling.
- **Model Evaluation**: Metrics such as accuracy, precision, recall, F1-score, and ROC-AUC are used to evaluate the model performance.
- **Deployment**: The model is deployed using Flask/Django for easy access and use in a web application.

## Dataset

The dataset used for this project includes the following features:

- **id**: Unique identifier for each individual
- **gender**: Gender of the individual
- **age**: Age of the individual
- **hypertension**: Whether the individual has hypertension (0: No, 1: Yes)
- **heart_disease**: Whether the individual has heart disease (0: No, 1: Yes)
- **ever_married**: Marital status of the individual
- **work_type**: Type of occupation of the individual
- **Residence_type**: Type of residence (Urban/Rural)
- **avg_glucose_level**: Average glucose level in blood
- **bmi**: Body Mass Index of the individual
- **smoking_status**: Smoking status of the individual
- **stroke**: Whether the individual had a stroke (0: No, 1: Yes)

## Requirements

To run this project, you will need the following libraries:

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Flask/Django (for deployment)

You can install the required libraries using the following command:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn flask
