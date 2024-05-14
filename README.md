# Introduction
Time series forecasting is a crucial aspect of data analysis and decision-making across various industries. In the context of security, accurately predicting the number of attacks on a specific website can enable proactive measures to mitigate potential threats. This project aims to develop machine/deep learning models capable of forecasting the number of security attacks based on historical time series data. By leveraging statistical methods and modeling techniques, the models provide insights into future attack trends, assisting organizations in strategizing and enhancing security measures.

## :ledger: Index

- [About](#beginner-about)
- [Usage](#zap-usage)
- [Development](#wrench-development)
  - [Pre-Requisites](#notebook-pre-requisites)
  - [Developmen Environment](#nut_and_bolt-development-environment)

##  :beginner: About
This project revolves around developing predictive models for forecasting security attacks on a specific website. The input data consists of a time series dataset containing the daily number of attacks observed over a year. The dataset may exhibit typical patterns such as daily and weekly cycles, sudden spikes, and potential outliers. The objective is to preprocess the data and design robust machine/deep learning solutions capable of handling the inherent unpredictability and seasonality of attacks. Three different approaches are explored in this project: using Facebook Prophet, Simple Exponential Smoothing (SES), and Long Short-Term Memory (LSTM) networks.

## :zap: Usage
If you intend to contribute to the development of this project, adhere to the following guidelines:

###  :electric_plug: Installation
#### Facebook Prophet Method
- Install the required libraries using pip install pandas numpy prophet.
- Load the historical time series data from a CSV file.
- Preprocess the data by handling missing values and outliers.
- Define the Prophet model and fit it to the data.
- Forecast the attacks and evaluate the model using Root Mean Square Error (RMSE).

#### SES Method
- Install the required libraries using pip install pandas numpy statsmodels scikit-learn.
- Load the historical time series data from a CSV file.
- Preprocess the data by handling missing values and outliers.
- Define the Simple Exponential Smoothing (SES) model and fit it to the data.
- Forecast the attacks and evaluate the model using RMSE.

#### LSTM Method
- Install the required libraries using pip install pandas numpy scikit-learn keras.
- Load the historical time series data from a CSV file.
- Preprocess the data by handling missing values and outliers.
- Define the LSTM model architecture and train it on the data.
- Forecast the attacks using the trained model and evaluate the forecast using RMSE.

##  :wrench: Development
If you wish to contribute to the development of this project, follow the guidelines below:

### :notebook: Pre-Requisites
Ensure you have the following prerequisites installed:

- Python
- Prophet
- statsmodels
- scikit-learn
- keras
- Access to historical time series data

###  :nut_and_bolt: Development Environment
To set up the development environment, proceed as follows:

- Clone the repository.
- Install the required dependencies.
- Set up your preferred development environment (e.g., Jupyter Notebook, IDE).
- Begin exploring and enhancing the existing models or implementing new forecasting techniques.

Ensure that the environment is properly configured and dependencies are installed before commencing development work.

