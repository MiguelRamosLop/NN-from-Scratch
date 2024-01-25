# NN-from-Scratch
## Building a NN from Scratch

This repository contains a simple neural network implementation from scratch trained on the MNIST dataset, with subsequent enhancements for improved performance. 
From this implementation: https://www.kaggle.com/code/wwsalmon/simple-mnist-nn-from-scratch-numpy-no-tf-keras/notebook, several changes were made to improve performance and accuracy.

### Key Components:
#### MNIST Dataset:
The model is trained and tested on the MNIST dataset, consisting of grayscale images of hand-written digits (0-9).
https://www.kaggle.com/competitions/digit-recognizer/data (from kaggle)

#### Neural Network from Scratch:
The initial implementation includes a basic neural network architecture for digit classification.
Improvements:
- Hyperparameter tuning with adaptive learning rate scheduling.
- Kaiming initialization for improving weiths initialization.
- Applying James-Stein Paradox statistical phenomenon basics and L2 regularization technique to prevent overfitting.
- Mini-batch gradient descent for improved efficiency.

### NN Workflow Overview
![Workflow Overview](NN%20workflow%20overview.jpg)
