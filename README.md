# Bitcoin Price Time Series Prediction

A time series analysis and prediction project focused on Bitcoin (BTC-USD) price data. This project uses historical Bitcoin price data from Yahoo Finance to perform time series analysis and forecasting.

## Project Overview

- **Data Source**: Yahoo Finance BTC-USD historical data
- **Time Period**: October 31, 2016 - October 31, 2022
- **Data Frequency**: Daily data resampled to monthly averages
- **Last Updated**: January 2, 2025

## Acknowledgments

This project was inspired by various open-source cryptocurrency analysis projects on GitHub. While the specific source project cannot be directly cited, this implementation builds upon the collective knowledge and approaches shared by the data science community. If you recognize any specific code patterns or methodologies that should be attributed, please open an issue for proper acknowledgment.

## Dependencies

- pandas
- numpy
- matplotlib
- statsmodels
- scipy
- yfinance
- yahoo_fin
- pandas_datareader

## Project Structure

The project is implemented in a Jupyter notebook (`TS_Final_Project.ipynb`) that contains:
- Data collection from Yahoo Finance
- Data preprocessing and resampling
- Time series analysis
- Statistical testing and modeling
- Visualization of results

## Data Processing

- Daily Bitcoin price data is collected using the yfinance API
- Data is resampled to monthly frequency using mean values
- Time series analysis includes statistical tests and modeling

## Academic Usage

If you use this code for academic work, please acknowledge it as:

```
This work builds upon an implementation of Bitcoin price prediction using time series analysis,
developed in 2023. The original implementation was inspired by open-source cryptocurrency
analysis projects on GitHub.
