# 🐱🐶 Cat vs Dog Image Classifier

## Overview
This project uses a Convolutional Neural Network (CNN) built with TensorFlow/Keras to classify images as either cats or dogs.

## Dataset
- Source: Kaggle Cats vs Dogs Dataset
- Classes:
  - Cats
  - Dogs

## Technologies Used
- Python
- TensorFlow/Keras
- OpenCV
- NumPy
- Matplotlib

## Model Architecture

Conv2D(32) → MaxPooling2D

Conv2D(64) → MaxPooling2D

Conv2D(128) → MaxPooling2D

Flatten

Dense(128)

Dense(64)

Dense(1, activation='sigmoid')

## Training Results

- Training Accuracy: ~99%
- Validation Accuracy: ~98-99%

## Sample Predictions

### Dog Image
Prediction Score: 0.9855
Predicted Class: Dog

### Cat Image
Prediction Score: 0.2204
Predicted Class: Cat
