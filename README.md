# Deep Neural Network for Regression (From Scratch)

## Overview
This project demonstrates a foundational understanding of Deep Learning mathematics by implementing a fully connected Deep Neural Network entirely from scratch using pure **NumPy**. No high-level frameworks (like TensorFlow or PyTorch) were used. The model is built to solve a regression problem predicting California Housing prices.

## Mathematical Implementation
The core achievement of this project is the manual implementation of neural network mechanics:
- **Forward Propagation:** Matrix dot products and activation function applications.
- **Backward Propagation:** Manual calculation of gradients using the chain rule to minimize the Sum Squared Error (SSE) loss function.
- **Optimization:** Custom Gradient Descent implementation to update weights and biases.
- **Activations:** Hand-coded ReLU (with its derivative) for hidden layers and Linear activation for the output layer.

## Architecture & Hyperparameters
Based on iterative tuning, the final network architecture was defined as:
- **Input Layer:** Features from the California Housing dataset.
- **Hidden Layer 1:** 64 Neurons (ReLU)
- **Hidden Layer 2:** 32 Neurons (ReLU)
- **Output Layer:** 1 Neuron (Linear)
- **Learning Rate:** 0.0001
- **Epochs:** 1000

## Technologies Used
- Pure Python & NumPy (for core Neural Network calculus and linear algebra)
- Pandas (for data manipulation)
- Scikit-Learn (strictly for Data Preprocessing: Scaling and Splitting)
