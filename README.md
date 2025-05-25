# Algorithmic Trading Project

## Overview
This project implements and evaluates two leveraged trading strategies on the SPTL bond ETF for the period from January 1, 2023, to December 31, 2023, using the Effective Federal Funds Rate (EFFR) as the risk-free rate. The strategies include a constant-leverage Buy & Hold strategy and a Moving Average Crossover strategy, both operating under a leverage factor of 10 and an initial capital of $100,000. Performance is assessed using Sharpe and Calmar ratios.

## Project Structure
The project consists of the following components:
- **algo_trade.ipynb**: A Jupyter Notebook containing the Python code for:
  - Data preparation (downloading SPTL ETF data and EFFR, aligning dates, computing returns).
  - Implementation of the Buy & Hold and Moving Average Crossover strategies.
  - Calculation of performance metrics (Sharpe and Calmar ratios).
  - Visualization of returns and PnL components.
- **algo_report.pdf**: A report detailing the methodology, including data preparation, strategy descriptions, PnL calculations, and performance evaluation.
- **EFFR.xlsx**: An Excel file containing the Effective Federal Funds Rate data (not included in this repository; must be sourced separately from the New York Fed website).

## Prerequisites
To run the code, ensure you have the following installed:
- Python 3.x
- Required Python libraries:
  ```bash
  pip install yfinance pandas numpy matplotlib pandas-datareader openpyxl
