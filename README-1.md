# Handwritten Digit Classification using CNN (PyTorch)

##  Project Overview
This project implements a Convolutional Neural Network (CNN) using PyTorch to classify handwritten digits from the MNIST dataset. The model consists of three convolutional layers, ReLU activation, Max Pooling, and fully connected layers to classify digits from 0 to 9. The model achieved a *99.29% test accuracy* on the MNIST dataset.

##  Features
•⁠  ⁠Implemented using PyTorch
•⁠  ⁠Three Convolutional Layers
•⁠  ⁠ReLU Activation Function
•⁠  ⁠Max Pooling Layers
•⁠  ⁠Fully Connected Layers
•⁠  ⁠Adam Optimizer
•⁠  ⁠CrossEntropy Loss
•⁠  ⁠Achieved *99.29% Test Accuracy*

##  Dataset
•⁠  ⁠*Dataset:* MNIST
•⁠  ⁠*Image Size:* 28 × 28 pixels
•⁠  ⁠*Image Type:* Grayscale (1 Channel)
•⁠  ⁠*Classes:* 10 (Digits 0–9)

##  Model Architecture

Input (1 × 28 × 28)
        │
        ▼
Conv2D + ReLU + MaxPool
        │
        ▼
Conv2D + ReLU + MaxPool
        │
        ▼
Conv2D + ReLU + MaxPool
        │
        ▼
Flatten
        │
        ▼
Fully Connected Layer
        │
        ▼
Output Layer (10 Classes)


##  Technologies Used

•⁠  ⁠Python
•⁠  ⁠PyTorch
•⁠  ⁠Torchvision
•⁠  ⁠NumPy

##  Results

| Metric        | Value 
|---------------|------------------
| Model         | CNN 
| Dataset       | MNIST 
| Test Accuracy | *99.29%* 
| Optimizer     | Adam 
| Loss Function | CrossEntropyLoss 

 
##  Author
*Vikas Bajpai*

## ⭐ Conclusion

The proposed CNN model successfully classified handwritten digits from the MNIST dataset with an impressive *99.29% test accuracy*, demonstrating the effectiveness of Convolutional Neural Networks for image classification tasks.