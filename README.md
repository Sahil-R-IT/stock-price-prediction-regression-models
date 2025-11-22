# Stock Price Prediction using Regression Models

This project compares four regression models — **Linear, Lasso, Ridge, and ElasticNet** — to predict Apple (AAPL) stock prices using historical market data from Yahoo Finance.


# Project Overview
- Goal: Predict next-day Apple (AAPL) stock prices.
- Domain: Finance & Investment Analytics.
- Data Source: Yahoo Finance (2020–2024).
- Tickers Used: AAPL, AMZN, MSFT, QQQ, ^GSPC.



# Models Implemented

| Model      | Regularization Type | Key Parameters          | R² | MSE | RMSE |          Insights             |
| ---------- | ------------------- | ----------------------- | -- | --- | ---- | ------------------------------|
| Linear     | None                | —                       |0.83|17.23| 4.15 |  Best in-Sample Performance   |
| Lasso      | L1                  | alpha=0.1               |0.75|34.32| 5.85 |      Feature Selection        |
| Ridge      | L2                  | alpha=1.0               |0.74|35.98| 5.99 |    Stable, lower Variance     |
| ElasticNet | L1 + L2             | alpha=0.1, l1_ratio=0.5 |0.75|35.00| 5.91 |     Balanced trade-off        |



# Visualization
- RMSE Bar Chart comparing model errors.
- Feature Importance (from Lasso coefficients).



# Key Insights
- Linear Regression performed best in-sample.
- Regularized models (Ridge, Lasso, Elastic Net) improved generalization.
- Elastic Net provided a balanced bias–variance trade-off.


# Files in Repository
- P2_Model_Comparison.ipynb (Main Summary)
- P2_Linear_Regression.ipynb
- P2_Lasso_Regression.ipynb
- P2_Ridge_Regression.ipynb
- P2_ElasticNet_Regression.ipynb



## Author
# Sahil Rabadiya
Data Analyst | Passionate about Finance & Machine Learning
srabadi1@asu.edu |  [Linkedin](https://www.linkedin.com/in/sahil-rabadi/)
