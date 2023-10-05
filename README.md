# Simple Linear Regression using PyTorch

This repository contains a simple implementation of linear regression using PyTorch. The code demonstrates how to create a linear regression model, define a loss function, and perform optimization using Stochastic Gradient Descent (SGD). The example uses synthetic data generated with the help of scikit-learn.

## Prerequisites

Make sure you have the following dependencies installed:

- Python
- PyTorch
- scikit-learn
- matplotlib

You can install the required packages using the following command:

```bash
pip install torch scikit-learn matplotlib
```

## How to Run

Clone this repository and run the Python script:

```bash
python simple_linear_regression_using_pytorch.py
```

The script generates synthetic data, creates a linear regression model, trains the model using SGD, and plots the training loss over epochs.

## Code Explanation

The main components of the code include:

- **Data Generation:** Using scikit-learn's `make_regression` function to generate synthetic data with 10 features and 1 target variable.

- **Model Definition:** Defining a linear regression model using PyTorch's `nn.Linear`.

- **Loss Function:** Using Mean-Square Error (`nn.MSELoss`) as the loss function.

- **Optimization:** Using Stochastic Gradient Descent (`torch.optim.SGD`) as the optimizer.

- **Training Loop:** Training the model for a specified number of epochs, calculating the loss, and updating the model parameters.

- **Visualization:** Plotting the training loss over epochs using Matplotlib.

## Results

The script will output a plot showing how the loss decreases over training epochs. This demonstrates the learning process of the linear regression model.
