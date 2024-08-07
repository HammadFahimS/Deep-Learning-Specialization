# Deep Neural Network Assignments - Week 4

## Overview

This repository contains the Week 4 programming assignments from the "Neural Networks and Deep Learning" course by Deeplearning.AI, offered through Coursera and taught by Andrew Ng. The assignments include building a deep neural network from scratch and then applying it to a supervised classification task using cat images.

## Assignments

### 1. Building your Deep Neural Network: Step by Step

#### Objective

Develop a deep neural network using Python and NumPy. This assignment involves implementing all the functions required to build a deep neural network. This includes:

- Initializing parameters
- Implementing forward propagation (linear -> linear -> activation)
- Computing the loss
- Implementing backward propagation (linear -> activation gradients)
- Updating parameters (gradient descent)

#### Key Concepts

- Layered architecture of deep neural networks
- Activation functions: ReLU, sigmoid
- Loss functions
- Backpropagation

### 2. Deep Neural Network - Application

#### Objective

Utilize the deep neural network built in the previous assignment to classify images as containing a cat or not. This involves:

- Loading the data set (cat/non-cat)
- Preprocessing the dataset
- Implementing the model functions
- Tuning the model parameters
- Assessing the accuracy of the model

#### Key Concepts

- Binary classification
- Overfitting vs Underfitting
- Regularization techniques
- Model accuracy and evaluation metrics

## Technologies Used

- Python 3.8
- NumPy
- h5py (for handling H5 file format)
- Matplotlib (for visualizing the data)

## Results

Implementing the deep neural network model successfully classifies images with high accuracy. The model can achieve impressive results on the provided dataset by tuning hyperparameters such as the learning rate, number of iterations, and number of layers.

## Setup and Installation

To run these notebooks:

1. Ensure Python 3.x is installed.
2. Install required packages:
   ```bash
   pip install numpy matplotlib h5py
   ```
3. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
4. Navigate to the directory containing the notebooks and run:
   ```bash
   jupyter notebook
   ```

## Contributions

Feel free to fork the repository, make changes, and create a pull request if you have ways to improve the model or add additional functionalities.

---

This README provides a comprehensive guide to your assignments for Week 4, making it easier for other students or reviewers to understand and use your work effectively.
