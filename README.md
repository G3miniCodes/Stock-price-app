## 📈 Stock Prediction App
Welcome to the Stock Prediction App! This interactive web application leverages historical stock data and advanced time-series forecasting techniques to predict future stock prices. Built using Streamlit, yfinance, and Prophet, this app provides a user-friendly interface to explore and visualize stock predictions.

## 🚀 Features
- Select Stocks: Choose from a variety of popular stocks like Apple (AAPL), Google (GOOG), Microsoft (MSFT), and GameStop (GME).
- Customizable Prediction Period: Adjust the slider to forecast stock prices for the next 1 to 4 years.
- Interactive Visualizations: View raw stock data and compare opening and closing prices over time.
- Forecasting with Prophet: Predict future stock prices using the robust Prophet forecasting model.
- Forecast Components: Analyze forecast components such as trend and seasonality.

## 📊 How It Works
- Data Loading: The app fetches historical stock data using the yfinance library.
- Data Visualization: Displays raw stock data, including opening and closing prices, with interactive charts.
- Time-Series Forecasting: Utilizes the Prophet model to generate future stock price predictions.
- Interactive Forecasting: Visualize forecasted data and analyze its components with Plotly charts.

## 💻 Getting Started
Prerequisites
Ensure you have Python and the required libraries installed. You can install the necessary packages using pip:
 - pip install streamlit yfinance prophet plotly
Running the App
To launch the Stock Prediction App, navigate to the directory containing the script and run:
 - streamlit run main.py
(Replace app.py with the filename of your Streamlit script if it's different.)

## Interacting with the App
Select Stock: Use the dropdown menu to choose a stock for prediction.
Adjust Prediction Period: Move the slider to select the number of years for the forecast.
Explore Data: View raw data and interactive charts to analyze historical trends and forecast results.

## 📁 Files Included
main.py: Main Streamlit application script.
README.md: This file with information about the app.
