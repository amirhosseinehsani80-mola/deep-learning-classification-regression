# Deep Learning Projects

This repository contains several deep learning experiments focusing on both classification and regression tasks. The projects are implemented in Python using TensorFlow, Keras, NumPy, Pandas, and Scikit-Learn. Each script explores a specific concept in neural networks, including regularization, weight analysis, optimization algorithms, hyperparameter tuning, and regression modeling.

## Fashion-MNIST Classification

The classification folder includes multiple multilayer perceptron (MLP) experiments trained on the Fashion-MNIST dataset. The goal is to understand how architectural choices, optimization functions, and hyperparameters affect performance.

### Regularization Study
An MLP with dropout and L2 regularization is trained and evaluated. The experiment demonstrates the influence of regularization on accuracy and stability during training.

### Weight Distribution Analysis
Two MLP models with different configurations are compared by analyzing their learned weight distributions. The results highlight how model complexity and regularization affect overfitting and generalization.

### Optimizer Comparison and Bayesian Search
Training performance is compared using Adam, Nadam, and RMSprop optimizers. Bayesian optimization is implemented to search for improved hyperparameters, illustrating automated tuning strategies.

### Hyperparameter Experiments
A large number of architectures are tested, including variations in depth, number of units, learning rate, and early stopping. The results show how different configurations influence accuracy and loss, and how model capacity interacts with optimization settings.

## House Price Regression
<img width="1206" height="1001" alt="image" src="https://github.com/user-attachments/assets/c5bb73aa-57f2-4def-9750-b9eacdf4cff3" />

The regression folder includes a neural network model trained to predict house prices. The dataset is preprocessed through scaling, one-hot encoding, and a logarithmic transform of the target variable. Two models with different depths are trained and compared based on mean squared error and mean absolute error. The project demonstrates how neural networks can be applied to tabular regression tasks and how preprocessing affects performance.

## Repository Structure

The repository is organized into classification and regression folders. Each Python script contains a complete experiment, including model definition, training, evaluation, and result discussion. A requirements file is included for easy environment setup.

## How to Run

Install the required libraries using the provided requirements file. Run any script directly to reproduce the experiment. Datasets should be placed in the data directory.

## Summary

This collection of projects demonstrates practical applications of neural networks across different tasks. It covers regularization, optimization, hyperparameter tuning, and regression modeling, providing a clear overview of core deep learning techniques.
