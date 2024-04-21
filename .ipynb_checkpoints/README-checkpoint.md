# COVID-19 Survival Prediction Model
This repository contains a TensorFlow model that analyzes Filipino health data from the COVID-19 pandemic to predict a patient's survival time and recovery status based on age and sex.

## Project Overview
This project addresses the challenge of predicting COVID-19 patient survival time and recovery status using a Feedforward Neural Network (FNN) built with TensorFlow. The model takes "Sex" and "Age" as input features and aims to estimate the following:
Survival Time: The number of days between the date of symptom onset and the date of recovery/death (removal date).
Recovery Status: Categorized as either "Recovered" or "Dead" based on the removal date.

## Model Architecture
The model employs a Feedforward Neural Network (FNN) architecture. The specific configuration, including the number of layers, neurons per layer, and activation functions, may be defined within the code (model.py). Experimentation with different hyperparameters can potentially be conducted to improve model performance.