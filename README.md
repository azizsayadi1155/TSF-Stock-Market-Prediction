# TSF-Stock-Market-Prediction

## Project Overview
This project aims to predict the performance of the S&P BSE SENSEX using a hybrid model that combines numerical analysis of historical stock prices and sentiment analysis of news headlines. The model utilizes machine learning techniques, specifically Long Short-Term Memory (LSTM) neural networks, to forecast future SENSEX values.

## Key Features
- Data collection from Yahoo Finance (SENSEX historical data) and Times of India (news headlines)
- Sentiment analysis of news headlines using TextBlob
- LSTM-based hybrid model for time series forecasting
- Integration of price data and sentiment scores for improved predictions
- 30-day future SENSEX value predictions

## Technologies Used
- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Scikit-learn for data preprocessing
- TensorFlow for building and training the LSTM model
- TextBlob for sentiment analysis

## Results
The hybrid model achieved promising results with:
- Train RMSE: 1133.42
- Test RMSE: 1119.29

These values indicate good performance, with a relative error of approximately 2.25% on both training and test sets.

## Future Improvements
- Incorporate additional features such as trading volume and economic indicators
- Experiment with advanced NLP techniques for sentiment analysis
- Implement ensemble methods to combine multiple models
- Develop a real-time prediction system

## Disclaimer
This project is for educational purposes only. Stock market predictions are inherently uncertain and should not be the sole basis for making investment decisions.
