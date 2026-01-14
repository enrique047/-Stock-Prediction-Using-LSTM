# Stock Prediction Using LSTM

Predict future stock prices using a **Long Short-Term Memory (LSTM)** deep learning model trained on historical stock data.

This project uses Python, TensorFlow/Keras, and real stock price data (e.g., from Yahoo Finance) to train an LSTM model that forecasts stock prices and visualizes predictions.

## Overview

Time-series forecasting of financial data is a challenging but interesting problem due to patterns and temporal dependencies. LSTM neural networks are well-suited for this because they can learn long-term patterns in sequential data.

In this project, we:
Fetch and preprocess historical stock price data
Train an LSTM model
Save and load trained models (`.h5`) for prediction
Visualize predictions vs actual prices
(Optional) Run a simple interactive app for prediction

## Features

Fetch stock price data (e.g., Yahoo Finance)  
Data preprocessing & scaling  
Train LSTM model for forecasting  
Save and load trained models  
Plot prediction vs actual price curves  
Optional UI for interactive predictions (using `app.py`)

## To Run
Make sure Streamlit is installed:

pip install streamlit

From the project root directory, run:

streamlit run app.py

This command starts a local web server and opens the Streamlit app in your browser.
You can then enter a stock ticker symbol to see predictions.
