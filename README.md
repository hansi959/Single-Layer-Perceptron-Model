Project Overview

This project is **Assignment 01** of the **Deep Learning Fundamentals** course, where  a Single-Layer Perceptron (SLP) was implemented to classify data from the Diabetes Dataset. The aim is to understand the basics of a perceptron model and its use in binary classification tasks.

Diabetes Dataset

The Diabetes Dataset consists of 768 records of patients, with 8 key features used to predict whether or not the patient has diabetes. These features include:

1. Pregnancies: Number of times pregnant
2. Glucose: Plasma glucose concentration (after 2 hours in an oral glucose tolerance test)
3. BloodPressure: Diastolic blood pressure (mm Hg)
4. SkinThickness: Triceps skinfold thickness (mm)
5. Insulin: 2-Hour serum insulin (mu U/ml)
6. BMI: Body mass index (weight in kg/(height in m)^2)
7. DiabetesPedigreeFunction: A function which scores likelihood of diabetes based on family history
8. Age: Age in years

The target variable (outcome) indicates whether the patient has diabetes or not.

Single-Layer Perceptron (SLP) Model

A Single-Layer Perceptron is the simplest form of a neural network, consisting of a single layer of neurons (or units) with direct connections from the input features to the output. It works as a binary classifier that attempts to predict one of two possible outcomes—in this case, whether or not a patient has diabetes.

Key Steps:
1. Preprocess the dataset (normalize/scale the features).
2. Train a Single-Layer Perceptron using the Keras Sequential API.
3. Use Focal Loss as the loss function and SGD optimizer.
4. Evaluate the model using accuracy, precision, recall, and F1-score.
