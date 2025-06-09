# ML Momentum Predictor

This project uses machine learning to predict short-term stock momentum based on technical indicators. It combines classic quant strategy ideas with modern classification models to evaluate whether the S&P 500 (SPY) will go up or down the next day.

## 📈 Project Overview

- **Target**: Next-day SPY price direction (up/down)
- **Features**: Moving average differentials, RSI, volatility, returns, Bollinger Bands, etc.
- **Models**: Logistic Regression, Random Forest, XGBoost
- **Strategy**: Backtest a trading strategy based on model predictions
- **Benchmark**: Compare to simple moving average crossover

## 🔧 How to Run

1. Install dependencies:
```bash
pip install -r requirements.txt
