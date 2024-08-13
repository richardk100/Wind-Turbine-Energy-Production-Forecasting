# Wind-Turbine-Energy-Production-Forecasting

This project involves analyzing and forecasting wind turbine energy production using time series decomposition and SARIMAX modeling. The dataset includes monthly energy production data, and the goal is to detrend the data, decompose it into its components, and forecast future energy production.

## Project Overview

- **Data Source:** Wind turbine energy production data (CSV file)
- **Tools Used:** Python, Pandas, Matplotlib, Statsmodels
- **Key Steps:**
  1. Loading and preprocessing the data
  2. Time series decomposition using seasonal decomposition
  3. Detrending the data using the first difference method
  4. Forecasting future energy production using SARIMAX
  5. Plotting actual vs. forecasted detrended energy production

## Project Structure

- `wind_turbine_energy_production.csv`: The dataset containing the energy production data.
- `energy_production_forecasting.py`: The Python script containing the code for data preprocessing, decomposition, detrending, and forecasting.
- `README.md`: This file, providing an overview of the project.

## Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/richardk100/Wind-Turbine-Energy-Production-Forecasting.git
