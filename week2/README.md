### Week 2 Assignments: Deep Learning Specialization

#### Introduction
This repository contains the programming assignments for Week 2 of Andrew Ng's "Neural Networks and Deep Learning" course, part of the Deep Learning Specialization on Coursera. The assignments focus on solidifying the basics of Python and NumPy essential for deep learning and applying these skills to build a logistic regression model from scratch using a neural network mindset.

#### Assignments Overview

1. **Python_Basics_with_Numpy.ipynb**
2. **Logistic_Regression_with_a_Neural_Network_mindset.ipynb**

### 1. Python Basics with Numpy
This Jupyter notebook introduces fundamental Python programming concepts and the NumPy library, which is crucial for scientific computing in Python. It provides a hands-on approach to understanding vectors and matrices operations, broadcasting, and other advanced features of NumPy that are extensively used in data science and deep learning.

#### Key Concepts Covered:
- **Python Lists vs. NumPy Arrays**: Understanding the performance benefits and functional advantages of NumPy arrays.
- **Vectorization**: Utilizing NumPy's vectorization capabilities to express algorithms without explicit looping.
- **Broadcasting and its Rules**: Learning how NumPy handles operations with arrays of different shapes.

#### Problems and Solutions:
The notebook includes several exercises that require implementing functions using NumPy operations. These exercises help solidify understanding of:
- Element-wise operations
- Matrix multiplication
- Broadcasting mechanics
- Computational efficiency improvements

The solutions provided in the notebook demonstrate efficient ways to manipulate data with NumPy, emphasizing the avoidance of loops in favor of vectorized operations, which are both cleaner and faster.

### 2. Logistic Regression with a Neural Network Mindset
This assignment delves into building a logistic regression classifier to recognize cats. Despite its simplicity, logistic regression can be framed as a very shallow neural network, making this an excellent exercise for understanding the basic neural network concepts.

#### Key Concepts Covered:
- **Logistic Regression**: The fundamentals of logistic regression and how it can be used for binary classification tasks.
- **Gradient Descent**: Implementing the gradient descent algorithm to optimize the loss function.
- **Cross-Entropy Loss**: Understanding how to compute the cost function in logistic regression.

#### Problems and Solutions:
The notebook guides through the steps to develop a logistic regression model that involves:
- Initializing parameters
- Calculating the cost function and its gradient
- Using gradient descent for optimization
- Evaluating the accuracy of the model

The final part of the assignment involves combining these steps into a model function and training this model on a set of labeled images to determine whether they contain a cat.

#### Results
Both exercises include tests that verify the correctness of the implemented functions, providing instant feedback on the implementation's accuracy. These exercises are critical for understanding and applying the mathematical foundations of machine learning algorithms in Python.

### Usage
To run these notebooks:
1. Clone the repository:
   ```bash
   git clone https://github.com/HammadFahimS/Neural-Networks-and-Deep-Learning/new/main/week2.git
   ```
2. Navigate to the Week 2 directory:
   ```bash
   cd Neural-Networks-and-Deep-Learning/new/main/week2
   ```
3. Open the Jupyter Notebooks in Jupyter Lab or Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
