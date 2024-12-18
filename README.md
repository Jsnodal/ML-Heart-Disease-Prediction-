# ML | Heart Disease Prediction Using Logistic Regression

This project demonstrates the use of machine learning for predicting heart disease risk using the **Logistic Regression** algorithm. The dataset used in this project is a cardiovascular dataset that provides the patient information and aims to predict whether the patient has a 10-year risk of future coronary heart disease (CHD).

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Deployment](#deployment)
- [License](#license)

## Overview
The goal of this project is to predict the likelihood of a patient suffering from heart disease based on several features such as age, cholesterol levels, blood pressure, smoking habits, and more. We use **Logistic Regression** to perform binary classification, where the target variable is whether a patient will have heart disease (1) or not (0).

We also explore **imbalanced class handling**, **feature selection**, and **model evaluation**.

## Dataset
The dataset used for this project comes from an ongoing cardiovascular study of residents in Framingham, Massachusetts. It contains over 4,000 records with 15 attributes. The attributes include:
- **age**: Age of the patient
- **sex**: Gender (male/female)
- **cigsPerDay**: Cigarettes smoked per day
- **totChol**: Total cholesterol level
- **sysBP**: Systolic blood pressure
- **glucose**: Glucose level
- **TenYearCHD**: Target variable (1 = heart disease, 0 = no heart disease)

## Model
We use **Logistic Regression** for this classification task. Key steps include:
1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling features.
2. **Model Training**: Training the logistic regression model using the training data.
3. **Model Evaluation**: Evaluating the model using accuracy, precision, recall, and F1 score.

The model was evaluated using various metrics to ensure its performance and also handled class imbalance using **class weights**.

## Installation
To get started with this project, clone the repository to your local machine:

```bash
git clone https://github.com/jsnodal/heart-disease-prediction.git
cd heart-disease-prediction
