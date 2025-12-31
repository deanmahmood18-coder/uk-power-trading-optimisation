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
base data
<img width="989" height="390" alt="image" src="https://github.com/user-attachments/assets/06211ddf-82f9-496b-84e9-a3968d6a09a2" />
electricity price by the hour
<img width="989" height="390" alt="image" src="https://github.com/user-attachments/assets/3e22989b-f68c-4348-adaf-1ecd55cbbb6b" />
current strategy unprofitable
<img width="989" height="390" alt="image" src="https://github.com/user-attachments/assets/52bdcc58-d87f-4e7f-8670-dd02e10db48b" />
perfect foresight benchmark
<img width="989" height="390" alt="image" src="https://github.com/user-attachments/assets/24a6ebc9-2bf7-4cd3-9b93-88086e999d60" />
LB optimised strategy
<img width="989" height="390" alt="image" src="https://github.com/user-attachments/assets/21feb04a-4272-4376-83d6-43da1c795e90" />
strategies compared 
<img width="989" height="390" alt="image" src="https://github.com/user-attachments/assets/90698211-93c4-47b9-a658-dd62b7499940" />



