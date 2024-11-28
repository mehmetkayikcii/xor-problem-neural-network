# xor-problem-neural-network
XOR Problem Solved with a Neural Network
This project implements a neural network to solve the logical XOR problem. The XOR function is non-linearly separable, making it an ideal example to demonstrate the capabilities of a multi-layer perceptron (MLP) with a hidden layer.

Features
Sigmoid Activation Function: Used to introduce non-linearity in the network.
Backpropagation: The network learns by minimizing the error using gradient descent.
->Training Data: Binary inputs ([0,0],[0,1],[1,0],[1,1]) with XOR outputs ([0,1,1,0]).

->Network Architecture: A single hidden layer with 2 neurons and 1 output neuron.

Code Structure

1- Function Definitions:

->sigmoid(net): Computes the sigmoid activation function.

->sigmoid_derivative(net): Computes the derivative of the sigmoid function for backpropagation.

2- Parameters:

->Number of epochs (130,000) and learning rate (0.1).
 
->Randomly initialized weights and biases for the hidden and output layers.

3- Training Loop:

->Forward Propagation: Computes the output of the hidden and final layers.

->Error Calculation: Calculates the error between the predicted and target outputs.

->Backpropagation: Updates weights and biases for both layers using the gradient of the error.

4-Model Testing:

->The trained model is tested on the XOR inputs, and the final predictions are displayed.
