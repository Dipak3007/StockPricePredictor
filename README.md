# StockPricePredictor

## Overview

StockPricePredictor is a machine learning project that predicts stock prices by analyzing historical stock data and incorporating news sentiment analysis. The project utilizes **Long Short-Term Memory (LSTM) neural networks** for accurate time series prediction. It also employs **Natural Language Processing (NLP)** for sentiment analysis on news data, categorized as positive, negative, or neutral.

## Features

- **LSTM Neural Network** based stock price prediction using the last 10 days' historical data.
- Integration of **NLP** for sentiment analysis on news data using **Logistic Regression**.
- Categorization of news events as positive, negative, or neutral for stock prices.
- Predicting the **stock trend** for the next few days.

## Tools and Libraries used

- Python 3.x
- Web Scrapper Chrome Extension
- YFinance Module
- Jupyter Notebook
- Pandas
- SciKit-Learn
- TensorFlow
- NLTK (Natural Language ToolKit)

## Project Structure

- `1News_Scrapping/`: Folder containing news datasets and code for news data preparation.
- `2NewsClassification/`: Folder dedicated for news sentiment analysis.
- `3MergedDataPreparation/`: Folder for preparing final dataset having news sentiment and closing price of stock for each day.
- `4MainModelTraining/`: Folder dedicated for LSTM Model Training.
- `5ModelTesting/`: Folder dedicated for Model Testing and calculating performance of the model.
- `6MainSentimentPrediction/`: Folder dedicated for predicting news sentiment for next 5 days for predicting the stock price.
- `Final_Prediction_Next5Days.ipynb`: Prediction of stock price for the next 5 days is done here using the model which was trained earlier.

## Future Work

1. **Enhanced User Interface Integration**
      - Explore opportunities to enhance the user interface (UI) to provide a more user-friendly and interactive experience. Consider incorporating data visualization tools that enable users to intuitively interpret the model's predictions and gain deeper insights into the factors influencing stock prices.

2. **Real-Time Data Feeds**
      - Investigate the integration of real-time data feeds to ensure that the model operates on the most up-to-date information. This would involve establishing a robust system for continuous data streaming, allowing the model to adapt to rapidly changing market conditions in real-time.

3. **Extended Geopolitical Factors**
      - Expand the incorporation of geopolitical factors beyond political indicators. Consider including additional qualitative factors such as social unrest, policy changes, or global events, and assess their impact on stock prices. This expansion could further refine the model's ability to capture the intricacies of market behavior.

4. **Risk Management Strategies**
      - Develop and implement risk management strategies based on the model's predictions. Investigate how the model can inform decision-makers on potential risks and uncertainties in the market, assisting them in crafting more resilient investment strategies.

5. **Cross-Asset Prediction**
      - Extend the predictive capabilities to encompass multiple financial instruments beyond stocks, such as commodities or currencies. Assess the feasibility of creating a comprehensive predictive model that spans various asset classes to offer a broader market perspective.
