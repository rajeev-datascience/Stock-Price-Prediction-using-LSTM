# Stock-Price-Prediction-using-LSTM
Project Overview
This project aims to predict stock prices using Long Short-Term Memory (LSTM) networks, a type of Recurrent Neural Network (RNN) well-suited for time series forecasting. The model is trained on historical stock data for Google (GOOG) and provides future price predictions with an emphasis on trend analysis.

Steps Involved

Data Extraction:

Utilized yfinance to fetch historical stock data.
Collected data from January 1, 2015, to the present date.

Data Preprocessing:

Normalized the data using MinMaxScaler.
Created time series sequences with a time step of 60 days.

Model Development:

Built an LSTM model using Keras with TensorFlow backend.
Configured the model with two LSTM layers, a dropout layer, and a dense output layer.
Trained the model on the prepared data.

Prediction & Visualization:

Predicted stock prices for both past and future data.
Visualized the actual stock prices, past predictions, and future predictions in an interactive and continuous graph.

Techniques Used
Long Short-Term Memory (LSTM): Leveraged LSTM networks for their ability to capture long-term dependencies in time series data.

Data Scaling: Applied Min-Max scaling to normalize the data for better model performance.

Sequence Creation: Created sequences of historical data to feed into the LSTM model.

Impact of the Model
The model showcases the potential of machine learning in financial forecasting. By accurately following trends and making future predictions, it provides valuable insights that can aid in data-driven decision-making for stock market investments.

Disclaimer
This project is for educational purposes only and should not be considered as financial or investment advice.
