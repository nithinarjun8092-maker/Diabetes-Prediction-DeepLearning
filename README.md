# Diabetes Prediction | Deep Learning & Keras

## Overview
A diabetes prediction system built using Artificial 
Neural Network (ANN) with Keras and TensorFlow on 
the Pima Indians Diabetes dataset.

## Dataset
- Name: Pima Indians Diabetes Dataset
- Records: 768 patients
- Features: 8 medical input variables
- Target: Diabetic (1) or Not Diabetic (0)

## Features Used
1. Number of times pregnant
2. Plasma glucose concentration
3. Diastolic blood pressure (mm Hg)
4. Triceps skin fold thickness (mm)
5. 2-Hour serum insulin (mu U/ml)
6. Body mass index (BMI)
7. Diabetes pedigree function
8. Age (years)

## Model Architecture
- Input Layer: 8 features
- Hidden Layer 1: 12 neurons (ReLU activation)
- Hidden Layer 2: 8 neurons (ReLU activation)
- Output Layer: 1 neuron (Sigmoid activation)

## Training Details
- Loss Function: Binary Crossentropy
- Optimizer: Adam
- Epochs: 40
- Batch Size: 10

## Results
- Model trained and evaluated on 768 records
- Model saved in JSON and H5 format
- Predictions generated on test samples

## Project Files
- train.py — Model training and saving
- prediction.py — Model loading and predictions
- pima-indians-diabetes.csv — Dataset

## Tools Used
Python | Keras | TensorFlow | NumPy | Deep Learning
