# Neural Network from Scratch

A fully functional neural network implementation from scratch in Python, provided as a Jupyter notebook (`nn-from-scratch.ipynb`). This project focuses on building, training, and evaluating a neural network (from first principles) designed for digit recognition tasks.

## Features

- Pure Python implementation – **no deep learning frameworks required**
- Step-by-step creation of essential NN components:
  - Forward & backward propagation
  - ReLU/Softmax activation functions
  - Weight & bias initialization
  - Gradient descent optimization
  - One-hot encoding for targets
  - Accuracy measurement
- Built-in data preprocessing, shuffle, and train/validate split
- Utilizes the [Kaggle/BinaryMNIST Digit Recognizer](https://www.kaggle.com/competitions/digit-recognizer) dataset
- Visualization of predictions and samples with Matplotlib

## Requirements

- Python 3.7+
- Jupyter Notebook
- numpy
- pandas
- matplotlib

You can install the requirements using:
`pip install numpy pandas matplotlib`



**Run all cells:**  
The notebook walks you through every step: data preprocessing, network construction, training, validation, and predictions.

## Main Components

- **Data Loading:** Reads, normalizes, and prepares digit image data (784 features per example)
- **Network Initialization:** Weight and bias setup for a two-layer network
- **Activation Functions:** Includes ReLU and softmax implementations
- **Forward & Backward Passes:** Complete code for training via gradient descent and backpropagation
- **Prediction & Accuracy:** Functions to evaluate performance on both train and dev sets
- **Visualization:** Uses `matplotlib` to plot predictions and mistakes

## Results

- Achieves >86% accuracy on the digit recognition task using a simple two-layer architecture.
- Prints training progress every 100 iterations.

