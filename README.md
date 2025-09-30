# Monte-Carlo-Simulation-of-my-favorite-stocks

This project applies Monte Carlo simulation to measure portfolio risk using a set of ETF's and stocks.

### What the notebook does
- Downloads stock data from Yahoo Finance  
- Calculates daily returns and builds an equal-weight portfolio  
- Runs Monte Carlo simulations to model thousands of return scenarios  
- Estimates Value at Risk (VaR) and Expected Shortfall (ES)  
- Visualizes simulated losses and stress tests with a -10% market shock  
- Compares Monte Carlo VaR with Historical VaR  

### How to run
1. Clone this repo  
2. Install dependencies:  
   ```bash
   pip install numpy pandas matplotlib yfinance ipywidgets
