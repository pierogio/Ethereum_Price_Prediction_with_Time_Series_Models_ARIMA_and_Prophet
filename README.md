# Analysis and Prediction of Ethereum Prices and Its Correlation with Other Assets:

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)  
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

The goal of this project is to create monthly predictions for the Ethereum cryptocurrency price and to identify correlations between its price fluctuations and the fluctuations of other financial assets for educational purposes only. It's important to note that cryptocurrency price prediction is challenging due to the extreme volatility of these assets.

What is Ethereum?

Ethereum is a decentralized blockchain platform and cryptocurrency introduced in 2015. It's known for its innovation with smart contracts, self-executing agreements written in code. Ethereum's native cryptocurrency is Ether (ETH), used for transactions and running smart contracts. It's a foundation for decentralized applications (DApps) across various industries and introduced the concept of Decentralized Autonomous Organizations (DAOs). Ethereum has undergone upgrades, like Ethereum 2.0, to improve scalability and efficiency. It remains a central player in the evolving blockchain and cryptocurrency space.

Consideration:

The dataset used in this model covers the period from 2017 to 2023. While significant changes in the data are observed from 2019 onwards, it's important to note that we have chosen not to exclude any data from the full time period for this project. We have opted to retain the entire time period in our analysis, despite the potential for poorer predictive results, to ensure a comprehensive understanding of the dataset's dynamics.

Models:

ARIMA Model

The Autoregressive Integrated Moving Average (ARIMA)model is a powerful time series forecasting method known for its adaptability and accuracy. Key points about the ARIMA model include:

Model Components: ARIMA combines three components - Autoregressive (AR), Integrated (I), and Moving Average (MA) - to capture complex time series patterns.

Strengths: ARIMA is adaptable, doesn't assume data distribution, provides accurate forecasts..

Prophet Model

Prophet is a forecasting model developed by Facebook for handling time series data. It uses an additive model approach, fitting non-linear trends by considering yearly, weekly, and daily seasonality, along with holiday effects.

One of the strengths of Prophet is its robustness in handling missing data, shifts in trends, and outliers. Notably, Prophet is designed specifically for time series data, which makes it unnecessary to perform normalization or standardization on the input data.

Correlation:

The objective is to analyze the correlations that may exist between Ethereum prices and the fluctuations of Bitcoin, Oil, Gold, Vanguard Information Technology ETF, Vanguard Energy Index Fund, and VIX.
