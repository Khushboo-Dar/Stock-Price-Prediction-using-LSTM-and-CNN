# 📈 Stock Price Prediction using LSTM and CNN

This project demonstrates how to use deep learning models (LSTM and CNN) to predict stock prices using historical data from Yahoo Finance. The chosen stock for this example is **Apple Inc. (AAPL)**. The models are trained on the closing prices and compared against actual stock prices.

---

## Project Overview

The project covers the following:

- Downloading historical stock price data (2010–2022)
- Preprocessing data with normalization and sequence generation
- Building and training LSTM and CNN models
- Visualizing actual vs predicted prices

---

## Technologies Used

- Python  
- yfinance
- pandas  
- TensorFlow / Keras
- scikit-learn
- matplotlib

---


---

## Models Used

### LSTM (Long Short-Term Memory)

A type of recurrent neural network (RNN) designed for sequence prediction. Ideal for capturing long-term dependencies in time series data.

### CNN (Convolutional Neural Network)

Though commonly used for image processing, CNNs can also learn spatial hierarchies in sequential data.

---

## Model Training

Both models are trained on sequences of 60 previous stock prices to predict the next price point.

- **Epochs:** 10  
- **Batch Size:** 32  
- **Loss Function:** Mean Squared Error  
- **Optimizer:** Adam

## Prediction Plots

### LSTM Model Prediction

![LSTM Prediction](images/Screenshot%20from%202025-04-20%2019-07-37.png)

### CNN Model Prediction

![CNN Prediction](images/Screenshot%20from%202025-04-20%2019-07-48.png)




