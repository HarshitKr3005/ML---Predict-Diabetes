# Diabetes Prediction ML Model

## Overview
This project implements a machine learning model to predict the likelihood of diabetes based on certain health indicators. The model is trained on a dataset containing various features such as glucose level, blood pressure, body mass index (BMI), etc., and their corresponding diabetes status.

## Dataset
The dataset used for training the model is sourced from Kaggle website. It consists of 800 samples and 8 features including:

- Glucose level
- Blood pressure
- BMI (Body Mass Index)
- Age
- Pregnancies
- Skin Thickness
- Insulin
- Diabetes Pedigree Function

  Target variable: Diabetes status (0 for non-diabetic, 1 for diabetic)

## Model Evaluation
The performance of the model is evaluated using accuracy. These metrics are computed on both the training and testing datasets to assess the model's generalization capability.

## Results
The trained model achieved the following performance metrics:

Accuracy on training set: 82%

Accuracy on testing set: 80%

## Future Work
Experiment with different machine learning algorithms and hyperparameters to improve model performance.

Explore feature engineering techniques to extract more meaningful information from the dataset.

Deploy the model as a web application or API for real-time predictions.
