# Coronary Heart Disease Prediction using Logistic Regression

This project aims to predict the likelihood of Coronary Heart Disease (CHD) within the next ten years based on a dataset from the Framingham Heart Study. Logistic regression is the model used.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Features](#features)
- [Model](#model)
- [Evaluation](#evaluation)

## Installation

To run this project, ensure you have Python installed on your system. Install the required packages by running:

```bash
pip install -r requirements.txt
```

## Dataset

The dataset used for this project is from the Framingham Heart Study. It includes risk factors such as:

- Age
- Gender
- Cigarettes per day
- Total cholesterol
- Systolic blood pressure
- Glucose level

The target variable is `TenYearCHD`, indicating whether the patient developed Coronary Heart Disease within the next 10 years.

## Features

The features used for predicting CHD are:

- `age`: Age of the patient.
- `Sex_male`: Gender (1 if male, 0 if female).
- `cigsPerDay`: Number of cigarettes smoked per day.
- `totChol`: Total cholesterol level.
- `sysBP`: Systolic blood pressure.
- `glucose`: Glucose level.

## Model

Logistic Regression is used as the classification model. After normalizing the features, the model is trained on 70% of the data and tested on 30%.

## Evaluation

The accuracy of the model is calculated using the `accuracy_score()` function from the `sklearn` library. The accuracy score provides insight into how well the model predicts CHD.

