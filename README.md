# Kidney Failure Classification Using ANN

## Overview
This project aims to classify kidney failure into two classes: 0 (no kidney failure) and 1 (kidney failure). The dataset is preprocessed using label encoding, one-hot encoding, and Min-Max scaling. An Artificial Neural Network (ANN) model is used for the classification task.

## Dataset
- **Classes**: 2 (0 for no kidney failure, 1 for kidney failure)
- **Data Preprocessing**:
  - **Label Encoding**: Converts categorical labels into numerical format.
  - **One-Hot Encoding**: Converts categorical features into a binary matrix representation.
  - **Min-Max Scaling**: Scales the feature values to a range between 0 and 1.

## Model Structure
The ANN model used for classification consists of the following layers:
- An input layer with 60 neurons, taking input of dimension 25 and using ReLU activation.
- A hidden layer with 40 neurons and ReLU activation.
- An output layer with a single neuron and sigmoid activation for binary classification.

The model is compiled with binary cross-entropy loss, Adam optimizer, and accuracy as the evaluation metric.

## Model Evaluation
The performance of the model is evaluated using the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**


