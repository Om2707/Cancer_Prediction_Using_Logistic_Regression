#Cancer Prediction Model

This repository contains a Google Colab notebook that analyzes a medical dataset to predict the presence of cancer based on various features. The dataset includes medical and lifestyle information for 1500 patients, structured to provide a realistic challenge for predictive modeling in the medical domain.

Dataset Description
The dataset contains the following features:

Age: Patient's age (20-80)
Gender: Gender (0 = Male, 1 = Female)
BMI: Body Mass Index (15-40)
Smoking: Smoking status (0 = No, 1 = Yes)
GeneticRisk: Genetic risk level for cancer (0 = Low, 1 = Medium, 2 = High)
PhysicalActivity: Hours per week spent on physical activities (0-10)
AlcoholIntake: Units of alcohol consumed per week (0-5)
CancerHistory: Personal history of cancer (0 = No, 1 = Yes)
Diagnosis: Cancer diagnosis status (0 = No Cancer, 1 = Cancer)
Project Overview
The notebook performs the following steps:

Exploratory Data Analysis (EDA): Visualizes the distribution of features and examines relationships.
Data Preprocessing: Splits the data into training and testing sets and scales the features.
Model Training: Trains a Logistic Regression model to predict cancer diagnosis.
Model Evaluation: Evaluates the model's performance using accuracy, ROC-AUC score, and classification report.
User Input Prediction: Provides a function to predict the probability of cancer based on user input.
