# NeuralNetwork-From-Scratch
Creation of a Neural Network for Classificazion from scratch

# README

## Introduction
This repository contains Python code implementing a simple neural network model, specifically a multilayer perceptron (MLP), along with examples of its application on the Iris dataset for classification tasks. The MLP is capable of using different activation functions and error functions, providing flexibility in model design and experimentation.

## Usage
To use the code, follow these steps:

1. Ensure you have Python installed on your system.
2. Clone this repository to your local machine.
3. Install the required dependencies using `pip install -r requirements.txt`.
4. Run the provided Python script containing the MLP implementation and examples.

Otherwise use Google Colab.
## Code Structure
The main components of the code are:

- **`Perceptron` class**: Represents a single neuron in the MLP. It includes methods for initialization, calculating outputs, and applying activation functions.
- **`Model` class**: Represents the MLP model, consisting of multiple layers of perceptrons. It includes methods for training the model (using backpropagation) and making predictions.
- **Activation Functions**: The code supports various activation functions, including step function, logistic sigmoid, hyperbolic tangent, and softmax.
- **Error Functions**: The code supports different error functions, such as square error and cross-entropy.

## Example Usage
The provided Python script demonstrates the usage of the MLP model on the Iris dataset. It includes examples of creating and training MLP models with different configurations (varying activation functions, layer sizes, and error functions). Additionally, it visualizes the training process by plotting the errors over epochs.

## Data
The Iris dataset is used for demonstration purposes. It consists of 150 samples with four features each and belongs to three different classes. The dataset is automatically fetched from the UCI Machine Learning Repository during execution.

## Dependencies
The code depends on the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

Ensure you have these libraries installed to run the code successfully.

## Acknowledgments
- The Iris dataset is sourced from the UCI Machine Learning Repository. 

Feel free to explore and experiment with the code. If you have any questions or feedback, please don't hesitate to reach out.
