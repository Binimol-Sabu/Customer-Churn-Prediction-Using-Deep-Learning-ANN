# Customer Churn Prediction Using Deep Learning (ANN)

This project implements an Artificial Neural Network (ANN) to predict customer churn using Keras/TensorFlow.

## Features
- Data preprocessing (scaling, encoding categorical variables)
- ANN model with dropout regularization
- Early stopping during training
- Performance evaluation metrics

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- tensorflow/keras

## Usage
1. Clone the repository
2. Open `ANN (1).ipynb` in Jupyter Notebook
3. Run all cells to train and evaluate the model

## Model Architecture
- Input layer (11 features)
- 2 hidden layers (6 units each) with ReLU activation
- Dropout layers (rate=0.1)
- Output layer with sigmoid activation

## Evaluation
- Binary crossentropy loss
- Accuracy metric
- Confusion matrix
- Classification report
