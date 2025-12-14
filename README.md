# Case Study 1: Data Mining in Financial Data

## Overview
This project focuses on the collection, processing, and analysis of financial stock data using Python. It demonstrates how to retrieve historical stock prices, perform data aggregation (weekly and monthly), and explore data through visualization to understand market trends and returns. The ultimate goal is to apply data mining and machine learning techniques to predict future stock prices, aiding in informed investment decisions.

## Features
- **Data Collection**: Automated downloading of 5-year historical stock data for major tech companies (e.g., GOOGL, AAPL, AMZN, MSFT, TSLA) using `yfinance`.
- **Data Preprocessing**: Handling missing values, checking for duplicates, and formatting timestamps.
- **Aggregation**: Resampling daily data into weekly and monthly averages for trend analysis.
- **Visualization**: Creating boxplots and other charts to identify outliers and visual the distribution of stock prices.
- **Return Analysis**: Calculation and plotting of daily, weekly, and monthly returns (functionality outlined).

## Prerequisites
- **Python 3.x**
- **Jupyter Notebook**
- **Libraries**:
  - `yfinance`: For fetching market data.
  - `pandas`: For data manipulation and analysis.
  - `matplotlib`: For data visualization.
  - `numpy`: For numerical operations.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Luna-CaiC/Data-Mining-in-Financial-Data.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Data-Mining-in-Financial-Data/Case1
   ```
3. Install required dependencies:
   ```bash
   pip install yfinance pandas matplotlib numpy
   ```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook case1_updated.ipynb
   ```
2. Run the cells sequentially to fetch data, process it, and view the analysis results.

## Project Structure
- `case1_updated.ipynb`: Main notebook containing the code for data collection, processing, and visualization.
- `stocks_data.csv`: (Generated) CSV file containing the downloaded raw stock data.
- `README.md`: Project documentation.

## Acknowledgments
- Data provided by [Yahoo Finance](https://finance.yahoo.com/) via the `yfinance` library.
