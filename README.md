# Building a Recurrent Neural Network - Step by Step

## Table of Contents

- [Introduction](#introduction)
- [Installation Instructions](#installation-instructions)
  - [Prerequisites](#prerequisites)
  - [Dependencies](#dependencies)
  - [Setup](#setup)
- [Usage](#usage)
  - [Running the Jupyter Notebook](#running-the-jupyter-notebook)
  - [Examples](#examples)
- [Features](#features)
- [Configuration](#configuration)
- [Notes on the Implementation](#notes-on-the-implementation)

## Introduction

This project provides a comprehensive, step-by-step implementation of a Recurrent Neural Network (RNN) using Python and Jupyter Notebooks. The implementation covers the basics of RNNs, including the forward and backward passes, Long Short-Term Memory (LSTM) networks, and their applications in Natural Language Processing (NLP) and other sequence tasks. This project is intended for those interested in understanding the internal mechanics of RNNs and LSTMs, from forward propagation to backpropagation.

## Installation Instructions

### Prerequisites

To run this project, you need to have the following installed:

- Python 3.7 or higher
- Jupyter Notebook or Jupyter Lab
- Internet access for installing additional libraries

### Dependencies

Make sure you have the following Python libraries installed:

- `numpy` for numerical computations
- `rnn_utils` (included in the repository)
- `public_tests` (included in the repository)

You can install the necessary packages using pip:

```bash
pip install numpy
```

### Setup

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/justinliu23/rnn-from-scratch.git
   ```
2. Navigate to the directory:
   ```bash
   cd repo-name
   ```
3. Install the required dependencies as mentioned above.
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open the file `Building_a_Recurrent_Neural_Network_Step_by_Step.ipynb` to start running the code step-by-step.

## Usage

### Running the Jupyter Notebook

To run the notebook, ensure all dependencies are installed and Jupyter Notebook is set up correctly. Open the notebook `Building_a_Recurrent_Neural_Network_Step_by_Step.ipynb` and execute the cells in order to follow the steps in building an RNN from scratch.

### Examples

The notebook includes detailed examples, such as:

- **Forward Propagation for Basic RNN**: Implement and run a single RNN cell and a forward pass for a sequence of input data.
- **Long Short-Term Memory (LSTM) Network**: Implement LSTM cells and the forward pass using the defined cells.
- **Backpropagation in Recurrent Neural Networks**: Compute gradients for both simple RNN and LSTM networks.

You can modify the code in the cells or use the notebook as a basis for developing your own RNN models.

## Features

- **Step-by-Step RNN Implementation**: Learn the fundamental concepts behind RNNs, including forward and backward propagation.
- **LSTM Networks**: Understand the use of LSTM cells to overcome the vanishing gradient problem common in traditional RNNs.
- **Backpropagation Through Time (BPTT)**: Includes detailed explanation and code for backpropagation through time for both RNNs and LSTMs.

## Configuration

- The notebook allows for configuration of hyperparameters, such as the number of hidden units, learning rates, and the number of layers in the network.
- Modify these configurations directly in the notebook cells to experiment with different network architectures.

## Notes on the Implementation

- The project uses custom utility functions provided in `rnn_utils.py` for forward and backward propagation calculations.
- `public_tests.py` includes test cases to validate the implementation.
- Make sure to run all cells in order, as the later parts of the notebook depend on variables and functions defined in earlier cells.
