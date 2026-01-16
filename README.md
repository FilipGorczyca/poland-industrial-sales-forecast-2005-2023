# poland-industrial-sales-forecast-2005-2023
Forecasting Polish industrial sold production (GUS, 2005–2023) using deterministic trend models and Holt’s method; comparison via ex-ante forecast error and point forecasts for 2024–2025
Industrial production forecasting (Poland, GUS)
This project forecasts sold production of industry (total) in Poland using annual data from 2005–2023 (GUS).
​
The goal is to produce point forecasts for 2024 and 2025 and compare several time-series/trend approaches.
Data
Variable: Sold production of industry (total), PKD 2007 sections B–E.
Frequency: Annual, 19 observations (2005–2023).​
Unit: PLN million, current prices.​
Source: GUS (Statistics Poland).​
Methods compared
Linear trend.​
Power trend.​
Exponential trend.​
3rd-degree polynomial trend.​
Holt’s exponential smoothing (trend).
Models are compared using goodness-of-fit (R² where applicable) and ex-ante forecast uncertainty expressed as relative forecast error (VSDT%).​
The final recommendation is the 3rd-degree polynomial trend, which provides the lowest VSDT% for both horizons.
