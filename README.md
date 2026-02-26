##🇧🇩 Bangladesh Commodity Price Intelligence System

A data-driven time series forecasting and market intelligence system designed to analyze, model, and predict essential commodity prices in Bangladesh.

This project combines econometric modeling (SARIMAX), external shock analysis (Flood, Ramadan, Seasonal effects), and interactive business intelligence visualization using Retool.

🎯 Project Objectives

Analyze historical commodity price behavior in Bangladesh

Measure impact of external shocks (Ramadan, Flood, Seasons)

Compare stationary (d=0) vs differenced (d=1) models

Understand innovation-driven volatility

Build a live decision-support dashboard

🧠 Methodology

Time Series Decomposition (Trend, Seasonality, Residual)

ACF / PACF diagnostics

SARIMAX modeling (with external regressors)

Shock & intervention analysis

Residual diagnostics and refitting

Forecast generation

External Variables Used:

Ramadan Effect

Flood Shock

Seasonal Structure (Winter, Pre-Monsoon, Monsoon, Post-Monsoon)

##🏗 Project Architecture
```
Bangladesh-Commodity-Price-Intelligence-System
│
├── Project Data
│   │
│   ├── Main Script
│   │   └── main_model_script.py
│   │        → Complete SARIMAX modeling pipeline
│   │        → External variable integration
│   │        → Forecast generation
│   │
│   ├── Model Performance
│   │   └── model_performance.csv
│   │        → MAE
│   │        → MSE
│   │        → RMSE
│   │        → MAPE
│   │
│   ├── Fitted Model
│   │   ├── D=0 (Level Model)
│   │   ├── D=1 (Differenced Model)
│   │   ├── ACF
│   │   ├── PACF
│   │   └── TSA Model (.pkl files)
│   │
│   ├── products wise data
│   │   ├── Individual Products Actual Data
│   │   ├── Products Predicted Data
│   │   │   ├── d=0
│   │   │   └── d=1
│   │   └── Data to Predict
│   │
│   └── TSD (Time Series Decomposition)
│
├── Live Retool Dashboard
│   ├── Dashboard Screenshot
│   └── Dashboard Link
│
└── README.md
```
📊 Commodities Modeled

Rice (চাল)

Wheat (আটা)

Onion (পিয়াজ)

Potato (আলু)

Broiler Chicken (মুরগি)

Chickpeas (ছোলা)

Soybean Oil (সয়াবিন তেল)

📈 Key Insights

Onion price significantly drops during Ramadan due to harvest timing and import policy.

Chicken price shows weak Ramadan significance due to rapid supply adjustment.

Seasonal coefficients vary by product due to storage capacity and perishability.

Market shows strong innovation-driven shock absorption behavior.

External variables sometimes become statistically weak due to structural volatility.

🖥 Live Dashboard

Interactive visualization built using Retool.
Provides:

Historical price trends

Model comparison (d=0 vs d=1)

Shock impact visualization

Forecast projection

🔗 Dashboard link available inside Live Retool Dashboard folder.

⚙️ Tech Stack

Python

Pandas

Statsmodels (SARIMAX)

Matplotlib

SQL

Retool

GitHub

🔍 Why This Project Matters

Bangladesh’s commodity market is highly shock-sensitive and innovation-driven.
This system attempts to statistically structure a market that is often perceived as unstable and intervention-driven.

It serves as:

A forecasting tool

A market behavior analysis system

A portfolio-grade econometric project

A policy-impact exploration framework

📌 Author

Sazid Shihab
Data Analyst | Time Series & Market Intelligence Enthusiast
