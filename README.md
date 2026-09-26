# AIML Recruitment 2026 - Abhijeet Mandal

## Candidate Details

- **Name:** Abhijeet Mandal
- **College:** SRM Institute of Science and Technology (SRMIST), Kattankulathur
- **Course:** B.Tech - Computer Science and Engineering (CSE Core)
- **Year:** 2nd Year

---

## Task Completed

### Task 2 - MNIST Neural Network Classification

This project implements a simple feed-forward neural network to classify handwritten digits from the MNIST dataset.

---

## Problem Statement

The objective is to build and evaluate a neural network capable of classifying grayscale images of handwritten digits from 0 to 9.

The project covers:

- Understanding the MNIST dataset
- Data preprocessing and normalization
- Building a neural network using TensorFlow/Keras
- Understanding activation functions
- Training and validating the model
- Evaluating the model using test accuracy and loss
- Generating a confusion matrix and classification report
- Performing a model modification experiment

---

## Approach

### 1. Dataset

The MNIST dataset contains:

- 70,000 grayscale handwritten digit images
- Image size: 28 × 28 pixels
- 10 classes: digits 0 through 9
- 60,000 training images
- 10,000 test images

### 2. Preprocessing

The following preprocessing steps were performed:

1. Loaded the MNIST dataset using TensorFlow/Keras.
2. Normalized pixel values from the range `[0, 255]` to `[0, 1]`.
3. Flattened each 28 × 28 image into a 784-element vector.
4. Used the training set for model training and validation.
5. Used the test set for final evaluation.

### 3. Neural Network

The baseline model uses the following architecture:

```text
Input Layer
784 neurons
    ↓
Hidden Layer
128 neurons + ReLU
    ↓
Output Layer
10 neurons + Softmax
