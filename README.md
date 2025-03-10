
# Neural Network from Scratch

This repository contains a Jupyter Notebook (`neural_network_from_scratch.ipynb`) that implements a neural network from scratch in Python. The notebook demonstrates fundamental concepts of neural networks, including forward and backward propagation, automatic differentiation, and training a Multi-Layer Perceptron (MLP) using gradient descent. It also includes visualization tools for computation graphs and comparisons with PyTorch for validation.

## Overview

The notebook builds a neural network step-by-step:
1. **Basic Function Exploration**: Starts with simple mathematical functions and their derivatives.
2. **Automatic Differentiation**: Implements a `Value` class for tracking operations and computing gradients via backpropagation.
3. **Neural Network Components**: Defines `Neuron`, `Layer`, and `MLP` classes to construct a fully functional neural network.
4. **Training**: Trains the MLP on a small dataset using mean squared error loss and gradient descent.
5. **Visualization**: Uses Graphviz to visualize the computation graph.
6. **Validation**: Compares results with PyTorch's autograd system.

## Prerequisites

To run the notebook, you'll need the following installed:
- **Python 3.10+**
- **Jupyter Notebook** or **JupyterLab**
- **Required Libraries**:
  - `numpy` (for numerical operations)
  - `matplotlib` (for plotting)
  - `graphviz` (for computation graph visualization)
  - `torch` (for PyTorch validation)
  - `random` (standard library, included with Python)

Install dependencies using pip:
```bash
pip install numpy matplotlib graphviz torch
