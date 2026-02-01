# Single Neuron Logistic Regression for Image Classification

This repository contains an implementation of a **single neuron (logistic regression)** model with a sigmoid activation function for binary image classification. The project was completed as part of a deep learning homework assignment.

## Overview

The notebook builds a binary classifier from scratch using NumPy. The task is to classify images as **cat** or **non-cat** by implementing the full learning pipeline manually.

Key components include:
- Parameter initialization
- Forward propagation with sigmoid activation
- Cost function computation
- Backpropagation
- Gradient descent optimization
- Model training and evaluation

## Dataset

The model is trained and tested using:
- `train_catvnoncat.h5`
- `test_catvnoncat.h5`

These datasets contain labeled RGB images stored in HDF5 format.


## Implementation Highlights

- No high-level ML libraries (e.g., TensorFlow, PyTorch)
- Pure NumPy-based implementation
- Clear separation of:
  - Forward propagation
  - Cost and gradient computation
  - Optimization loop
- Training loss monitoring across iterations

## Technologies Used

- Python
- NumPy
- h5py
- Matplotlib
- Jupyter Notebook
## Repository Structure

