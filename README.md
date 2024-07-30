# Heart Disease Prediction 🫀

Welcome to the Heart Disease Prediction project! This repository uses machine learning techniques to predict the likelihood of heart disease in patients based on medical data.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Features](#features)
4. [Machine Learning Models](#machine-learning-models)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [Acknowledgments](#acknowledgments)

## Introduction

Heart disease is a critical health issue worldwide. This project leverages machine learning to analyze patient data and predict the presence of heart disease, facilitating early detection and preventive care. The model is trained on a well-known dataset and achieves high accuracy in predicting heart disease risk.

## Dataset

The dataset used in this project is sourced from Kaggle and includes 13 key features for prediction such as age, sex, chest pain type, resting blood pressure, serum cholesterol, and others. The target variable indicates the presence of heart disease.

## Features

Key features include:

- **Age**: Age of the patient
- **Sex**: Gender of the patient
- **Chest Pain Type**: Type of chest pain experienced
- **Resting Blood Pressure**: Blood pressure at rest
- **Serum Cholesterol**: Cholesterol level in mg/dl
- **Fasting Blood Sugar**: Whether fasting blood sugar > 120 mg/dl
- **Resting ECG**: Results from the electrocardiogram test
- **Maximum Heart Rate Achieved**: Peak heart rate during exercise
- **Exercise Induced Angina**: Presence of angina induced by exercise
- **Oldpeak**: ST depression induced by exercise relative to rest
- **Slope**: Slope of the peak exercise ST segment
- **Number of Major Vessels**: Number of major vessels colored by fluoroscopy
- **Thalassemia**: Blood disorder status

## Machine Learning Models

We implemented a **Logistic Regression** machine learning algorithm to make this which achieved an accuracy of 81.96% which is not that bad and could be optimised by performing analysis on other algorithms too.

## Usage
- Input Data: Enter patient details such as age, cholesterol levels, and other relevant data.
- Prediction: Click the "Predict" button to determine the likelihood of heart disease.

## Contributing
Contributions are welcome! To contribute:

- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes and test them thoroughly.
- Submit a pull request with a detailed description of your changes.

## Acknowledgments
The dataset used in this project is available on Kaggle. Thanks to all contributors who have provided insights and improvements.
