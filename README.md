# Recurrent Neural Network (LSTM) Stock Model

## Description

This model uses stock data and twitter sentiment to generate a prediction of future market trends.

General process is as follows:

1. Get stock data from Google Finance (day-to-day data)

2. Get twitter sentiment for each day represented in stock data

3. Join data

4. Split into training windows of ```n``` timesteps where each timestep is one day (target is the next days closing price)

5. Train -> Predict -> Refine

## Performance Examples

![Alt text](https://github.com/als5ev/RNN_LSTM_Stock_Model/blob/master/img/demo.png?raw=true "Example 1")
