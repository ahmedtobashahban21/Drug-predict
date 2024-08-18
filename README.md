# Drug-predict

This repository contains a deep learning model using TensorFlow and LSTM networks to predict drug-related data.

## Overview

This project guides you through building and fine-tuning a Bidirectional LSTM model using TensorFlow, from data preprocessing to model evaluation and optimization.

## Steps to Run the Project

1. **Read Input Files:** Load and preprocess the data with the `read_file` function.
2. **Modify Input Data:** Convert text and labels into numerical indices, and pad sequences.
3. **Split Data:** Split data into training and validation sets using `train_test_split`.
4. **Build the LSTM Model:** Construct a Bidirectional LSTM model with an embedding layer.
5. **Evaluate Model Performance:** Train the model and assess its performance.
6. **Fine-tune Parameters:** Adjust input lengths, batch sizes, and epochs to improve accuracy.

## Dependencies

- Python 3.x
- TensorFlow
- NumPy
- scikit-learn
- sklearn-crfsuite

