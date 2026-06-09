# Cats vs Dogs Image Classification using CNN

## Project Overview

This project implements a Convolutional Neural Network (CNN) to classify images of cats and dogs.
The model is built using TensorFlow and Keras and trained on the Dogs vs Cats dataset from Kaggle.

The objective is to automatically determine whether an input image contains a cat or a dog.

---

## Features

* Binary image classification (Cat vs Dog)
* Built using TensorFlow and Keras
* Image preprocessing and normalization
* Training and validation pipeline using image datasets
* CNN architecture with multiple convolution and pooling layers
* Prediction on custom images

---

## Dataset

**Dataset:** Dogs vs Cats

Source: Kaggle Dogs vs Cats Dataset

The dataset contains thousands of labeled images of cats and dogs for training and testing.

**Note:** The dataset is not included in this repository due to GitHub file size limitations.

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* OpenCV
* Matplotlib
* Google Colab

---

## Model Architecture

The CNN architecture consists of:

1. Conv2D (32 filters) + MaxPooling2D
2. Conv2D (64 filters) + MaxPooling2D
3. Conv2D (128 filters) + MaxPooling2D
4. Flatten Layer
5. Dense Layer (128 neurons)
6. Dense Layer (64 neurons)
7. Output Layer (Sigmoid Activation)

The sigmoid activation function is used for binary classification.

---

## Data Preprocessing

* Images resized to 256 × 256 pixels
* Pixel values normalized from [0, 255] to [0, 1]
* Training and validation datasets created using TensorFlow utilities

---

## Training

* Optimizer: Adam
* Loss Function: Binary Crossentropy
* Evaluation Metric: Accuracy
* Epochs: 10

---

## Results

The model successfully learns to distinguish between cats and dogs and can be used to predict unseen images.

Example prediction:

* Output close to 0 → Cat
* Output close to 1 → Dog

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/Riya-Rajak/cats_vs_dogs_classifier.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
cats_vs_dogs_classification.ipynb
```

4. Run all cells sequentially.

---

## Future Improvements

* Data augmentation
* Transfer learning (VGG16, ResNet50, MobileNet)
* Hyperparameter tuning
* Model deployment using Flask or Streamlit
* Improved accuracy with deeper architectures

---

## Author

Riya Rajak

B.Tech (Electronics & Telecommunication Engineering)
Shri Govindram Seksaria Institute of Technology and Science (SGSITS), Indore
