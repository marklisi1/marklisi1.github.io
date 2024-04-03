---
title: "Stock Recommendations: Explainable AI with Boosting Methods"
excerpt: "Using the stock market as a vehicle to demonstrate explainability in XGBoost, a complex deep learning approach. Quant/finance, XAI, XGBoost"
collection: portfolio
---

As an exercise to demonstrate the explanatory power of Shapley values, I trained an agent capable of giving stock recommendations from a ticker! The agent, an XGBoost model, takes a ticker as input and reads some key stats from Yahoo! Finance before giving a natural language recommendation as a BUY, HOLD, or SELL. It is also capable of applying different weights to different features for an investment, growth, or ESG portfolio.

I am not a finance person by trade, so the accuracy of these recommendations/the features chosen as representative of future success are certainly subject to scrutiny - the intent was more to demonstrate how computers can generate explanations from inscrutable technical processes. If you have advice on how to improve the model, never hesitate to reach out!

[You can scroll through the notebook here.](https://github.com/marklisi1/stockbot/blob/main/hw2.ipynb)

* Skills: Data processing, computer vision, deep learning, model optimization, CUDA/GPU programming
* Tools: XGBoost, yfinance, shap, Pandas, NumPy
