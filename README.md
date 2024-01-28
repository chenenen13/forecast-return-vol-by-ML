# Bot Trading using Machine Learning

## Project Overview
This project involves developing a Machine Learning model to predict stock returns for LVMH Moët Hennessy Louis Vuitton SE (MC.PA). Using historical stock data, the RandomForestRegressor model is trained to forecast future returns. These predictions are then leveraged to estimate future stock prices.

## Key Features
- **Data Acquisition**: Leverages `yfinance` to download historical stock data.
- **Feature Engineering**: Employs features such as lagged returns and moving averages.
- **Model Training**: Utilizes a RandomForestRegressor for its robustness and ensemble learning capabilities.
- **Return Prediction**: Forecasts future stock returns based on historical data.
- **Price Estimation**: Converts predicted returns to stock price projections.
- **Evaluation**: Assesses model accuracy using Mean Squared Error (MSE) against actual market data.

## Visualization
Includes plots that visually compare the model's predicted values against actual market prices and returns, providing insights into the model's performance.


![image](https://github.com/chenenen13/forecast-return-vol-by-ML/assets/122288399/cc653b83-5eab-40c6-b2f7-a565d89ec2ee)
