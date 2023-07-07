# Machine Learning Helper Functions

This repository contains a collection of helper functions to assist with machine learning tasks. These functions have been created to aid in tasks such as data loading and preprocessing, model evaluation, and directory operations. 

## Table of Contents
- [Functions](#functions)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Functions

### 1. `load_and_preprocess_image`

This function loads an image file and applies preprocessing steps such as resizing and normalization.

### 2. `make_confusion_matrix`

A utility function to generate a confusion matrix from predicted and true labels.

### 3. `create_tensorboard_callback`

This function creates a TensorBoard callback for monitoring and visualizing model training progress.

### 4. `compare_history`

A function to compare training history between different models and plot their performance metrics.

### 5. `calculate_results`

This function calculates various evaluation metrics such as accuracy, precision, recall, and F1-score from predicted and true labels.

### 6. `walk_through_directory`

A helper function to iterate through a directory and retrieve file paths matching specific criteria.

## Installation

To use these helper functions, you can clone the repository using the following command:


## Usage

Once you have cloned the repository, you can import the required functions into your Python scripts or Jupyter notebooks as follows:

```python
from ml_helpers import load_and_preprocess_image, make_confusion_matrix, create_tensorboard_callback, compare_history, calculate_results, walk_through_directory
