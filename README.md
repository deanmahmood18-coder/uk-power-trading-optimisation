# UK Power Trading & Battery Optimisation

**Recommended reading order:**
1. `03_client_legacy_strategy.ipynb` – rule-based strategy currently used by the client  
2. `04_optimised_strategies.ipynb` – benchmark and optimised strategies with quantified uplift

## Overview
This project evaluates trading strategies for a battery energy storage asset operating in the UK power market. 
It compares a client-style legacy strategy with improved alternatives to demonstrate the value of optimisation.

## Structure
- `01_data_loading.ipynb`: Data ingestion and visualisation  
- `02_price_analysis.ipynb`: Price volatility and arbitrage intuition  
- `03_client_legacy_strategy.ipynb`: Rule-based trading strategy currently used by the client  
- `04_optimised_strategies.ipynb`: Benchmark and optimised strategies with comparison  

## Key Insights
- Simple rule-based strategies can destroy value due to inefficient cycling and poor exit timing  
- Volatility alone does not guarantee profitability  
- Constrained optimisation materially improves trading outcomes  
- A significant proportion of theoretical value can be captured using practical optimisation methods  

## Tools
Python, pandas, matplotlib, cvxpy

## Disclaimer
This project is for educational purposes only and does not constitute investment advice.
