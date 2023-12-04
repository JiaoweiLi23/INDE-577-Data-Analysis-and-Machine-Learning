# Neural Network with Multilayer Perceptron

## Overview

This Jupyter notebook provides a comprehensive guide to understanding and implementing a Multilayer Perceptron (MLP), a fundamental neural network architecture in machine learning. The notebook covers the structure, algorithm, implementation, and evaluation of an MLP model, using the Fashion-MNIST dataset for demonstration.

## Structure of Neural Network

- **Neurons**: The basic computational units of the neural network, receiving inputs and producing an output based on an activation function.
- **Layers**: Comprising an input layer, one or more hidden layers, and an output layer. The hidden layers perform computations and transfer information from input to output.

## Algorithm of MLP

1. **Initialization**: Define the network structure and initialize weights and biases.
2. **Forward Propagation**: Input data is processed layer-by-layer through the network.
3. **Cost Function**: The error between the predicted and actual output is calculated.
4. **Backpropagation**: Update the weights and biases based on the gradient of the error.
5. **Iteration**: Repeat the process for a specified number of epochs or until satisfactory performance is achieved.
6. **Evaluation**: Assess the model's performance on a separate test set.
7. **Prediction**: Use the trained network for making predictions on new data.

## Implementation

- **Dataset**: Fashion-MNIST, a collection of 70,000 grayscale images in 10 fashion categories.
- **TensorFlow**: Used for loading and processing the Fashion-MNIST dataset.
- **Neural Network**: Implementation of forward pass, prediction, and mean squared error (MSE) functions, alongside a class `DenseNetwork` for the MLP model.
- **Training**: The network is trained using stochastic gradient descent, and the MSE is monitored.
- **Evaluation**: The trained model's performance is evaluated based on its classification accuracy on test data.

## Results

- The model shows a significant decrease in MSE after training.
- The classification accuracy on the test data is 0.851, indicating effective learning and generalization.
- The results demonstrate the power of MLPs in handling complex pattern recognition tasks.

## Conclusion

Multilayer Perceptrons are versatile and powerful, capable of modeling intricate relationships in data. This notebook demonstrates their practical application in image classification, highlighting both their strengths and the challenges involved in their implementation.
