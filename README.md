# Stock Price Forecasting via Financial News Sentiment Analysis

This project focuses on forecasting stock prices by analyzing the sentiment of financial news articles. Using machine learning models such as GRU, LSTMs, and BERT, the project explores the impact of news sentiment on stock price movements, specifically for Reliance Industries.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Data Collection](#data-collection)
- [Methodology](#methodology)
- [Models Used](#models-used)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)

## Overview
This project analyzes 1,700 financial news articles related to Reliance Industries. By leveraging Natural Language Processing (NLP) models, we extract sentiment information from these articles and use them to predict stock price movements. The primary objective is to explore the relationship between public sentiment in financial news and stock price fluctuations.

## Features
- **Sentiment Analysis**: Sentiment extraction from financial news using NLP models.
- **Stock Price Forecasting**: Prediction of stock prices based on news sentiment and historical data.
- **Machine Learning Models**: Implementation of state-of-the-art models like GRU, LSTMs, and BERT for sentiment analysis and prediction.
- **Data Visualization**: Visualization of stock prices and sentiment impact over time.

## Data Collection
- **News Articles**: Collected through web scraping techniques, gathering a total of 1,700 news articles related to Reliance Industries.
- **Stock Prices**: Historical stock prices were sourced from public APIs and financial databases.

## Methodology
1. **Data Collection**: Web scraping of financial news articles and gathering historical stock prices.
2. **Data Preprocessing**: Cleaning and structuring data for further analysis.
3. **Sentiment Analysis**: Using BERT models to extract sentiment from the news articles.
4. **Feature Engineering**: Combining sentiment data with stock price history to create a dataset for forecasting.
5. **Stock Price Prediction**: Using LSTM and GRU models to predict future stock prices based on sentiment and price history.

## Models Used
- **GRU (Gated Recurrent Units)**: Applied for capturing sequential dependencies in stock price data.
- **LSTM (Long Short-Term Memory)**: Used to model the relationship between news sentiment and stock prices over time.
- **BERT (Bidirectional Encoder Representations from Transformers)**: For accurate sentiment analysis of financial news.

## Results
- **Sentiment Accuracy**: The sentiment analysis using BERT achieved an accuracy of 90%.
- **Stock Price Forecasting**: The LSTM model showed significant performance in predicting stock prices, integrating sentiment data with historical stock data for more accurate results.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/stock-price-forecasting.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Run the sentiment analysis on the collected news articles:
    ```bash
    python sentiment_analysis.py
    ```
2. Use the LSTM model for stock price prediction:
    ```bash
    python stock_price_prediction.py
    ```
