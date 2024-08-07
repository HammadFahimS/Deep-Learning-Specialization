# Planar Data Classification with One Hidden Layer

#### Overview
This repository contains the programming assignment for Week 3 of Andrew Ng's "Neural Networks and Deep Learning" course, part of the Deep Learning Specialization on Coursera. This assignment, titled "Planar Data Classification with One Hidden Layer," is designed to demonstrate the capability of a simple neural network to classify data that is not linearly separable.

#### Objective
The primary objective of this assignment is to implement and train a neural network with one hidden layer to classify planar data. This project illustrates the basic principles of neural network architecture, forward and backward propagation, and how non-linear decision boundaries are modeled.

#### Assignment Description
Students are tasked with building a 2-class classification neural network featuring a single hidden layer. This involves writing code to initialize the network, perform forward and backward propagation, compute losses, and update the network's parameters based on the gradient descent optimization algorithm.

#### Key Concepts Covered
- **Neural Network Architecture**: Detailed understanding of how a neural network with a single hidden layer is structured including the input, hidden, and output layers.
- **Activation Functions**: Exploration of non-linear activation functions such as tanh and their effect on the neural network's ability to capture complex patterns.
- **Loss Functions**: Calculation of cross-entropy loss to evaluate the performance of the network.
- **Backpropagation**: Detailed mechanism of how gradients are calculated in the network and used to update weights to minimize the loss function.

#### Implementation Details
The implementation involves several components integrated into a Python Jupyter notebook:
1. **`layer_sizes()`**:
   - Determines the size of the input layer based on the dataset features.
   - Sets the size of the hidden layer (number of hidden units, a hyperparameter).
   - Defines the size of the output layer, which is determined by the classification task (binary classification in this case).

2. **`initialize_parameters()`**:
   - Initializes the weights and biases for all layers of the network with small random values (weights) and zeros (biases).

3. **`forward_propagation()`**:
   - Implements the forward propagation using matrix multiplications and activation functions.
   - Calculates the output of the network for given inputs, which involves computing activations at the hidden layer and the output layer.

4. **`compute_cost()`**:
   - Computes the cross-entropy cost function, comparing the predicted outputs to the actual labels to gauge performance.

5. **`backward_propagation()`**:
   - Implements backward propagation to calculate the gradient of the loss function with respect to the weights and biases.
   - This involves computing derivatives and using the chain rule to propagate errors back through the network.

6. **`update_parameters()`**:
   - Updates the network parameters (weights and biases) using the gradients computed during backpropagation according to the learning rate.

7. **`nn_model()`**:
   - Integrates all the functions above into a complete model.
   - Includes setting the number of iterations for training and invoking the forward and backward propagation methods iteratively.

8. **`predict()`**:
   - Uses the trained parameters to predict a class label for each example in the test dataset.
   - Converts probabilities to class labels based on a threshold (typically 0.5 for binary classification).

#### File Structure
- **Planar_data_classification_with_one_hidden_layer.ipynb**: The Jupyter notebook containing the complete implementation and detailed explanations.

#### How to Run
To run this assignment notebook:
1. Clone the repository:
   ```bash
   git clone https://github.com/HammadFahimS/Neural-Networks-and-Deep-Learning
   ```
2. Navigate to the directory containing the notebook:
   ```bash
   cd Neural-Networks-and-Deep-Learning/week3
   ```
3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook Planar_data_classification_with_one_hidden_layer.ipynb
   ```

#### Contributions
We welcome contributions to improve the code, add new features, or enhance the explanations. Please fork the repository and submit a pull request with your changes.

#### License
This project is licensed under the MIT License - see the LICENSE.md file for details.
