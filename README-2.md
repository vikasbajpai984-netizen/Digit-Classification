# MNIST Handwritten Digit Classification using RNN

This project implements a *Recurrent Neural Network (RNN)* using *PyTorch* to classify handwritten digits from the *MNIST dataset*. Instead of using a CNN, each 28×28 image is treated as a sequence of 28 rows, allowing the RNN to learn spatial patterns sequentially.

## Project Overview

•⁠  ⁠Dataset: MNIST Handwritten Digits
•⁠  ⁠Framework: PyTorch
•⁠  ⁠Model: Recurrent Neural Network (RNN)
•⁠  ⁠Optimizer: Adam
•⁠  ⁠Loss Function: CrossEntropyLoss
•⁠  ⁠Number of Classes: 10 (Digits 0–9)

## Dataset

The MNIST dataset contains:

•⁠  ⁠60,000 training images
•⁠  ⁠10,000 testing images
•⁠  ⁠Image size: 28 × 28 pixels
•⁠  ⁠Grayscale images

The dataset is automatically downloaded using ⁠ torchvision.datasets.MNIST ⁠.

## Model Architecture

•⁠  ⁠Input Size: 28
•⁠  ⁠Sequence Length: 28
•⁠  ⁠Hidden Size: 128
•⁠  ⁠Number of RNN Layers: 1
•⁠  ⁠Fully Connected Layer:
  - Input: 128
  - Output: 10

Each image is reshaped from:


(batch_size, 1, 28, 28)
to
(batch_size, 28, 28)


where:

•⁠  ⁠Sequence Length = 28
•⁠  ⁠Input Size = 28

The RNN processes one row of the image at each time step.

## Technologies Used

•⁠  ⁠Python
•⁠  ⁠PyTorch
•⁠  ⁠Torchvision

## Training

The model is trained using:

•⁠  ⁠Optimizer: Adam
•⁠  ⁠Loss Function: CrossEntropyLoss

During training:

•⁠  ⁠Forward Pass
•⁠  ⁠Loss Calculation
•⁠  ⁠Backpropagation
•⁠  ⁠Parameter Update

are performed for every batch.

## Evaluation

After training, the model is evaluated on the MNIST test dataset.
Accuracy is calculated using:
Accuracy = (Correct Predictions / Total Samples) × 100

## Expected Performance

A simple RNN on the MNIST dataset typically achieves *96–98% test accuracy*, depending on the number of epochs and hyperparameters.

## Author

*Vikas Bajpai*

---
This project was developed for learning and implementing Recurrent Neural Networks (RNNs) using PyTorch on the MNIST handwritten digit classification dataset.
