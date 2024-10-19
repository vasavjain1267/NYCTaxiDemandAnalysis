Taxi Demand Forecasting using Time Series Analysis
This project demonstrates how to forecast daily taxi demand in New York City using the yellow taxi trip dataset. 
The analysis leverages time series modeling techniques, including SARIMA, to predict future taxi demand based on historical trip data.
Dataset:-
The dataset used in this project is the "NYC Yellow Taxi Trip Data" from Kaggle. The code automatically downloads the dataset using the Kaggle API.
SARIMA Model:-
A Seasonal AutoRegressive Integrated Moving Average with Exogenous Regressors (SARIMAX) model is trained on the trip_count using exogenous variables like trip_distance, extra, and rush_hour. 
The model is then used to forecast the taxi demand.
Future Work:-
Fine-tune the SARIMA model for better accuracy.
Experiment with other time series models like ARIMA, Prophet, or LSTM.
Include more exogenous variables to improve demand prediction.
