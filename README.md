# Time-Series-Forecasting
Time Series Forcasting
⸻

Stock Price Forecasting using ARIMA and SARIMA Models

Project Overview

This project aims to forecast the stock prices of Tesla and Apple for the next 12 months using time series forecasting techniques. Specifically, we use ARIMA (AutoRegressive Integrated Moving Average) and SARIMA (Seasonal ARIMA) models to make predictions. The goal of this project is to provide insight into future stock price movements based on historical data.

Project Structure

The project is organized as follows:

/stock-price-forecasting
│
├── /data                    # Folder containing historical stock data for Tesla and Apple
├── /notebooks               # Jupyter notebooks used for analysis and modeling
├── /src                     # Python scripts used for data preprocessing, modeling, and visualization
├── /models                  # Trained ARIMA and SARIMA models
├── README.md                # This file
└── requirements.txt         # List of dependencies required for the project

Data

The dataset used for this project consists of historical stock prices for Tesla and Apple, covering the time period from 2022-07 to 2025-07. The data contains:
	•	Date
	•	Stock Price (USD)

The data can be found in the data folder and is used for training the ARIMA and SARIMA models.

Methods Used
	1.	ARIMA Model:
	•	ARIMA (AutoRegressive Integrated Moving Average) is a popular time series forecasting method. It models a time series as a linear combination of its past values, error terms, and differences.
	•	ARIMA is applied when the time series does not exhibit strong seasonality.
	2.	SARIMA Model:
	•	SARIMA (Seasonal ARIMA) is an extension of the ARIMA model that includes seasonal components. This model is better suited for data that exhibits clear seasonal trends, like stock prices.

Steps for Forecasting
	1.	Data Preprocessing:
	•	Clean and prepare the historical stock price data.
	•	Handle missing values, perform stationarity tests, and transform data when needed.
	2.	Modeling:
	•	Fit the ARIMA and SARIMA models to the historical data.
	•	Perform model evaluation to tune parameters and improve forecasting accuracy.
	3.	Forecasting:
	•	Generate forecasts for the next 12 months based on the trained models.
	4.	Visualization:
	•	Plot historical data and predicted values using matplotlib to visualize the trends and forecasted values.

Requirements

To run the code in this repository, you’ll need to install the dependencies listed in the requirements.txt file. Use the following command to install them:

pip install -r requirements.txt

Required Libraries
	•	pandas
	•	numpy
	•	matplotlib
	•	statsmodels
	•	yfinance
	•	seaborn
	•	scikit-learn

Usage
	1.	Clone the Repository:

git clone https://github.com/yourusername/Time-Series-Forecasting.git


	2.	Install Dependencies:
Navigate to the project folder and install the required libraries:

cd stock-price-forecasting
pip install -r requirements.txt


	3.	Run the Jupyter Notebooks:
	•	Open notebooks/tesla_stock_forecast.ipynb for Tesla’s stock price prediction.
	•	Open notebooks/apple_stock_forecast.ipynb for Apple’s stock price prediction.
	4.	Forecasting:
	•	Execute the code in the notebooks to train the ARIMA and SARIMA models and generate the stock price forecasts for the next 12 months.
	•	Visualize the forecast results alongside the historical stock prices.

Results

The project provides the following outputs:
	•	ARIMA Forecast for Tesla and Apple for the next 12 months.
	•	SARIMA Forecast for Tesla and Apple for the next 12 months.
	•	Comparison of the historical and forecasted stock prices in graphical form.

Contributing

We welcome contributions! To contribute to this project, please follow these steps:
	1.	Fork the repository.
	2.	Create a new branch (git checkout -b feature-branch).
	3.	Commit your changes (git commit -am 'Add new feature').
	4.	Push to the branch (git push origin feature-branch).
	5.	Submit a pull request.

License

This project is licensed under the MIT License - see the LICENSE file for details.

⸻
