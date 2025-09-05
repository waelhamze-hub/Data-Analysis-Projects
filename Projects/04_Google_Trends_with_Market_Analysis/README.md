# GOOGLE TRENDS — MARKETS & UNEMPLOYMENT ANALYSIS

This project investigates whether **Google search popularity** relates to real-world economic and financial data.  
We explore links between search volume and **Tesla stock price**, **Bitcoin price**, and the **U.S. unemployment rate**.

## Objectives
- Compare **Tesla stock price** with Google Trends search interest.  
- Analyze whether **Bitcoin searches** move with BTC prices.  
- Explore if searches for **“unemployment benefits”** anticipate or follow changes in the U.S. unemployment rate.  
- Handle missing values, align different time frequencies (daily vs monthly), and build clear visualizations.  

## Dataset
- **Files (CSV in `data/` folder):**
  - `TESLA Search Trend vs Price.csv`
  - `Bitcoin Search Trend.csv`
  - `Daily Bitcoin Price.csv`
  - `UE Benefits Search vs UE Rate 2004-19.csv`
  - `UE Benefits Search vs UE Rate 2004-20.csv`
- **Sources:**
  - [FRED — U.S. Unemployment Rate](https://fred.stlouisfed.org/series/UNRATE)  
  - [Google Trends](https://trends.google.com/trends/explore)  
  - [Yahoo Finance — Tesla (TSLA)](https://finance.yahoo.com/quote/TSLA/history?p=TSLA)  
  - [Yahoo Finance — Bitcoin (BTC-USD)](https://finance.yahoo.com/quote/BTC-USD/history?p=BTC-USD)  

## Tools & Libraries
- **Python**
- **Pandas** → cleaning, resampling, merging time series  
- **Matplotlib** → visualizations (dual-axis plots, rolling averages)  
- **Jupyter Notebook** (VS Code)

## Analysis & Results
- **Tesla:** Search interest spikes around large price movements, but not always before them.  
- **Bitcoin:** Big rallies coincide with surges in search activity, though causality is not clear.  
- **Unemployment:** Searches for *unemployment benefits* closely mirror the unemployment rate, especially during crisis periods.  
- **Resampling & Alignment:** Daily BTC prices resampled to **monthly** enabled fair comparison with monthly Google Trends data.  

## Conclusion & Insights
- Google Trends provides a **proxy for public attention**, useful for contextualizing market and economic data.  
- Search data tends to **lag or coincide** with real-world events, rather than predict them perfectly.  
- When combined with financial/economic data, Google Trends can highlight **behavioral dynamics** that raw numbers miss.  
