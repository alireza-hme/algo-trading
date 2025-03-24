# Algo Trading Course

This repository contains assignments from my university's Algorithmic Trading course. It includes various projects and strategies, with the primary focus on a PineScript strategy that demonstrates key trading concepts.

## Strategy Overview

- **PineScript Version:** 6

- **Indicators Used:** 
  - EMA (Exponential Moving Average)
  - SMA (Simple Moving Average)
  - MACD (Moving Average Convergence Divergence)
  - RSI (Relative Strength Index)
  - VWAP (Volume Weighted Average Price)

- **Logic:**  
  The strategy utilizes:
  - EMA and SMA crossover for generating buy signals.
  - MACD and RSI for confirming trend direction and signal strength.
  - Volume filters to ensure sufficient market participation.
  - A defined trading period based on a custom start time and a three-month window.

## How to Use

1. **Open the Strategy:**  
   Open the `.pine` file in TradingView's Pine Editor.

2. **Add to Chart:**  
   Copy and paste the code into the editor and add it to your chart to visualize and backtest the strategy.