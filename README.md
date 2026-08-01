\# Retail Sales Forecasting



Time series forecasting of daily retail sales using Holt-Winters Exponential 

Smoothing, built on 5 years of historical data (2013-2017) from the Store 

Item Demand Forecasting dataset.



\## Key Findings

\- Sales show a consistent upward trend over the 5-year period, alongside a 

&#x20; strong, repeating yearly seasonal pattern confirmed via seasonal decomposition

\- Holt-Winters achieved an MAE of 5.52 and RMSE of 7.01 on the 2017 test set, 

&#x20; outperforming a naive seasonal baseline (MAE 6.05, RMSE 7.64) by roughly 9%

\- An interactive Plotly chart demonstrates the seasonal pattern generalizes 

&#x20; across multiple store-item combinations, not just the one modeled



\## Scope

Analysis focuses on one store-item pair (Store 1, Item 1) as a deliberate 

simplification for a first forecasting project.



\## Tools Used

\- Python (pandas, matplotlib, plotly)

\- statsmodels (Exponential Smoothing, seasonal decomposition)

\- Jupyter Notebook (via VS Code)



\## Dataset

\[Store Item Demand Forecasting Challenge](https://www.kaggle.com/competitions/demand-forecasting-kernels-only/data)

