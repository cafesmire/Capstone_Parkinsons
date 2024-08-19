---

# Predicting Freezing of Gait in Patients with Parkinson's

This repository contains Jupyter Notebooks that demonstrate various approaches to freezing of gait episode prediction using different types of neural networks, including RNN, LSTM, GRU, and ANN. The repository also includes data preprocessing steps and visualizations to aid in understanding the results.

## Table of Contents

- [Overview](#overview)
- [Notebooks](#notebooks)
  - [Data Preparation](#data-preparation)
  - [ANN Prediction](#ann-prediction)
  - [RNN Prediction](#rnn-prediction)
  - [LSTM Prediction](#lstm-prediction)
  - [GRU Prediction](#gru-prediction)
- [Acknowledgments](#acknowledgments)

## Overview

This project aims to explore different neural network architectures for effectively predicting the presence of freezing of gait episodes in patients suffering from Parkinson's disease. The datasets are preprocessed, and several models are trained and evaluated, including:

- **Recurrent Neural Network (RNN)**
- **Long Short-Term Memory (LSTM)**
- **Gated Recurrent Unit (GRU)**
- **Artificial Neural Network (ANN)**

Each approach is documented in its respective notebook, with visualizations provided to help interpret the performance of the models.

## Notebooks

### Data Preparation
- **File:** `data_prep.ipynb`
- **Description:** This notebook covers the preprocessing of the time series data, including normalization, splitting into training and testing datasets, and reshaping the data for input into neural networks.
- 
### ANN Prediction
- **File:** `ann_prediction.ipynb`
- **Description:** This notebook applies a basic Artificial Neural Network (ANN) to the time series data. It serves as a comparison to the more complex RNN-based models.
- 
### RNN Prediction
- **File:** `rnn_prediction.ipynb`
- **Description:** This notebook implements a Recurrent Neural Network (RNN) for time series predictions. It includes the model architecture, training process, and evaluation metrics.

### LSTM Prediction
- **File:** `lstm_prediction.ipynb`
- **Description:** This notebook focuses on using Long Short-Term Memory (LSTM) networks, which are a type of RNN designed to capture long-term dependencies in time series data.

### GRU Prediction
- **File:** `gru_prediction.ipynb`
- **Description:** This notebook showcases the Gated Recurrent Unit (GRU) model, which is another variant of RNNs that is computationally more efficient than LSTMs while still addressing the vanishing gradient problem.

## Acknowledgments
- This project was inspired by various tutorials and resources on time series prediction using neural networks.
- Special thanks to the open-source community for providing the tools and libraries used in this project.

---
