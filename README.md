# MNIST Handwriting Classification

A Convolutional Neural Network (CNN) built with Keras and TensorFlow to accurately classify handwritten digits from the MNIST dataset. 

## Overview
This project trains a custom CNN architecture to recognize standard 28x28 grayscale images of handwritten digits (0-9). The model implements advanced regularization techniques and achieves **99.61% test accuracy**.

## Key Features
* **Robust Architecture:** Utilizes multiple `Conv2D` blocks with `BatchNormalization` and `MaxPooling2D` for optimal feature extraction.
* **Preventing Overfitting:** Integrates `Dropout` layers and an `EarlyStopping` callback (monitoring validation loss).
* **Automated Checkpoints:** Uses `ModelCheckpoint` to automatically save the best-performing model state (`best_mnist_model.keras`).
* **Visual Evaluation:** Automatically generates plots for training/validation history and outputs a visual grid of sample predictions.

## Tech Stack
* **Python 3**
* **TensorFlow / Keras** * **NumPy**
* **Matplotlib**

## Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/Mr-Ritesh-J/mnist-classification.git](https://github.com/Mr-Ritesh-J/mnist-classification.git)
   cd mnist-classification
