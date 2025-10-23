# stock-forecast

## Description
This project provides a backend API and an ML model for stock price forecasting trained on the historical 
performance of the S&P 500.

## Functional Requirements
1. Users should be able to send a ticker name to receive predictions of the closing price.

## Non-functional Requirements
1. The API should answer with the predictions in under 1 second for 95% of the requests.
2. The system should be able to handle 1,000 concurrent requests.

## Core Features
* Forecast: Provides a JSON array of the predicted closing prices for a valid ticker.
* One central ML model trained on the historical data of the S&P 500 companies.