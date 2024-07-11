# Natural Gas Price Forecasting Model

## Overview

This IPython Notebook is designed to analyze historical natural gas price data and forecast future prices using a statistical modeling approach that integrates linear trend analysis with sinusoidal seasonal adjustments. This tool is essential for traders and analysts in commodities markets, specifically those dealing with natural gas storage contracts.

## Features

- **Data Loading**: Import historical natural gas prices from a CSV file.
- **Data Visualization**: Visualize price trends and seasonal patterns.
- **Model Development**: Develop a combined linear and sinusoidal model to forecast prices.
- **Price Prediction**: Functionality to predict prices for given future dates.
- **Extrapolation**: Extrapolate prices one year beyond the existing data for long-term planning.

## Data

The dataset includes monthly snapshot prices of natural gas from October 31, 2020, to September 30, 2024. The data is sourced from a reliable market data provider and is structured to show the closing price of natural gas at the end of each calendar month.

## Model

The forecasting model combines a linear regression component to capture long-term trends and a sinusoidal component to model the inherent seasonal variations in natural gas prices. This model is built to provide accurate price estimates for any specified date, facilitating strategic decision-making related to natural gas trading and storage.
