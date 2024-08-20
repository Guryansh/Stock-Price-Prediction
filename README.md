# Stock Price Prediction using LSTM

## Overview

This project utilizes a Long Short-Term Memory (LSTM) neural network to predict the closing stock prices of a company
based on the previous 60 days of stock price data. LSTM, a type of artificial recurrent neural network architecture, is
particularly effective for time series forecasting due to its ability to retain information over long periods.

## Authors

- [@Guryansh](https://www.github.com/Guryansh)

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Dataset](#dataset)
4. [Model Architecture](#model-architecture)
5. [Usage](#usage)
6. [Results](#results)

## Introduction

Stock market prediction is one of the most sought-after applications of machine learning due to its potential for
financial gain. This project leverages the power of LSTM networks to predict the closing price of stocks using
historical data. LSTM's ability to learn from sequential data makes it an ideal choice for this task.

## Installation

To run this project locally, ensure you have Python installed. You can install the necessary dependencies by running:

```bash
pip install -r requirements.txt
```

The required libraries include:

- TensorFlow
- NumPy
- Pandas
- Matplotlib

## Dataset

The dataset used in this project consists of historical stock prices, including the Open, High, Low, Close prices, and
Volume of Apple Stock. The model is trained using the closing prices for the past 60 days to predict the next day's
closing price.

## Model Architecture

The LSTM model is built using TensorFlow and consists of the following layers:

- LSTM Layer: Captures the time-dependent structure in the data.
- Dense Layer: Outputs the final prediction of the closing stock price.

## Usage

- Load the Dataset: Load your historical stock data into the notebook.
- Preprocess Data: Prepare the data by scaling and creating time-series sequences.
- Train the Model: Train the LSTM model on the preprocessed data.
- Predict Stock Prices: Use the trained model to predict future stock prices.

## Results

After training, the model will output a graph comparing the predicted stock prices with the actual stock prices,
providing a visual representation of the model's accuracy.

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)