# Stock Market Prediction using CNNs and LSTM

## Overview
This repository contains code for a research project conducted as part of the SET Conference, focusing on predicting stock market prices using deep learning techniques.

## Project Description
In this project, we utilize stock market datasets along with customer sentiment data obtained through the Stocktwits API. The workflow of the model involves:
1. **Sentiment Analysis**: Analyzing stock-related news to classify sentiments (good, bad, neutral) using company-specific data.
2. **Data Fusion**: Integrating sentiment analysis results with numerical stock data (such as prices and volumes).
3. **Stock Price Prediction**: Utilizing Long Short-Term Memory (LSTM) neural networks to predict future stock prices based on the fused data.
