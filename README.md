# MNIST TensorFlow Notebook

This project demonstrates training a neural network using TensorFlow to classify handwritten digits from the MNIST dataset. It serves as a beginner-friendly example for understanding deep learning concepts and working with image data in Python.

## Project Overview

The MNIST dataset consists of 70,000 grayscale images of handwritten digits (0-9), each sized 28x28 pixels. This project builds, trains, and evaluates a simple feedforward neural network model that can recognize these digits with high accuracy.

---

## Features

- Loads and preprocesses the MNIST dataset directly from TensorFlow datasets.
- Constructs a neural network with:
  - Input layer for 28x28 pixel images (flattened)
  - One or more hidden layers with ReLU activations
  - Output layer with softmax activation for 10 classes
- Compiles the model with categorical cross-entropy loss and Adam optimizer.
- Trains the model and plots training/validation accuracy and loss.
- Evaluates model performance on test data.
- Saves the trained model for future inference.

---

## Requirements

- Python 3.8 or higher
- TensorFlow 2.x
- Jupyter Notebook (optional, but recommended for interactive exploration)
- Matplotlib and NumPy (for visualization and data handling)

---

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/christt94/mnist-tensorflow.git
   cd mnist-tensorflow
