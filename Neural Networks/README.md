# Handwritten Digit Classification using Neural Networks

This project implements a neural network model for classifying handwritten digits from the MNIST dataset. The neural network is built from scratch using NumPy, and various activation functions (sigmoid, ReLU, and tanh) are explored. The model's performance is evaluated using accuracy and mean squared error (MSE) metrics.

## Dataset

The MNIST dataset is used for this project, which consists of 70,000 grayscale images of handwritten digits (0-9). The dataset is split into training and test sets, with 60,000 samples for training and 10,000 samples for testing.

## Preprocessing

The dataset is loaded using the `load_digits` function from `sklearn.datasets`. The features are scaled using `StandardScaler` from `sklearn.preprocessing`. One-hot encoding is applied to the target labels before training the model.

## Neural Network Architecture

The neural network architecture consists of an input layer, a hidden layer, and an output layer. The input layer has a size equal to the number of features in the dataset (64 for MNIST). The hidden layer size is set to 30, and the output layer size is equal to the number of classes (10 for MNIST).

## Activation Functions

Three different activation functions are implemented and evaluated:

1. **Sigmoid**: The sigmoid activation function is used in the hidden layer, and the output probabilities are obtained using the sigmoid function in the output layer.

2. **ReLU**: The ReLU (Rectified Linear Unit) activation function is used in both the hidden and output layers.

3. **Tanh**: The hyperbolic tangent (tanh) activation function is used in the hidden layer, and the output logits are obtained directly from the output layer without an activation function.

## Training and Evaluation

The neural network is trained using gradient descent and backpropagation. The training process is performed for a specified number of epochs, and the loss is calculated and printed every 100 epochs.

The model's performance is evaluated on the test set by calculating the accuracy and MSE. Different learning rates (0.01, 0.05, and 0.1) and numbers of epochs (500, 1000, and 1500) are tested to explore their impact on the model's performance.

## Results

The code prints the test accuracy and MSE for each combination of learning rate and number of epochs for all three activation functions (sigmoid, ReLU, and tanh). These results can be used to analyze the performance of the neural network and determine the optimal hyperparameters for the given task.

## Usage

To run the code, simply execute the provided Python script. The results will be printed to the console, showing the test accuracy and MSE for each combination of learning rate and number of epochs.

Note: This README assumes that the necessary libraries (numpy, sklearn, and matplotlib) are installed and available in the Python environment.