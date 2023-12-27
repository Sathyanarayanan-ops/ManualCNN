
# ManualCNN

This project aims to delve deep into understanding Convolutional Neural Networks (CNNs) by manually implementing a few CNN layers. The goal is to gain a comprehensive insight into constructing these layers from scratch.

## Overview

1. **Loading CIFAR10 & Initial Neural Network:**
   - Load the CIFAR10 dataset, preprocess it (e.g., normalization), and train a simple neural network using PyTorch functions. Achieve an initial accuracy of 52%.

2. **Hyperparameter Tuning:**
   - Perform basic hyperparameter tuning, raising the accuracy to 72%. Detailed comments reveal the iterative process and debugging efforts undertaken for optimization.

3. **Manual Neural Network Construction:**
   - Focus shifts to manually designing a neural network. Implement convolution operations using `scipy.signal.correlate2d` to mimic the convolution process. Backpropagation is then performed to compute gradients.

## Walkthrough

### Loading CIFAR10 & Initial Neural Network

The notebook provides a step-by-step process:
- Dataset loading from the web.
- Preprocessing steps, like pixel normalization.
- Training a basic neural network with appropriate loss functions and gradient descent, resulting in an initial 52% accuracy.

### Tuning Hyperparameters

This section emphasizes:
- Basic hyperparameter tuning for accuracy improvement, achieving 72%.
- Comments reflect the meticulous debugging and trial-and-error process undertaken to enhance model performance.

### Manual Neural Network Design

Exploration into manual CNN construction:
- Detailed explanation of manual convolution operations utilizing `scipy.signal.correlate2d`.
- Demonstration of forward pass effects through visualizations.
- Backpropagation for gradient calculation concerning input images, kernels, and biases.

## Visual Representations

![Forward Pass Effect](https://github.com/Sathyanarayanan-ops/ManualCNN/assets/57038667/f6c92693-0476-43aa-addd-2f4e3570db32)
![Forward Pass Visualization](https://github.com/Sathyanarayanan-ops/ManualCNN/assets/57038667/ba086539-7ca6-4972-9b3f-96ce375a1826)
![Backpropagation Gradient Visualization](https://github.com/Sathyanarayanan-ops/ManualCNN/assets/57038667/7b0c4ec8-35ed-479e-8780-55a33843114c)

This README provides a comprehensive walkthrough. The accompanying Jupyter notebook offers detailed line-by-line documentation for a deeper understanding.

---
