#  Multi-City AQI Forecast Automation

This repository automatically fetches real-time Air Quality Index (AQI) data
for **Delhi, Bangalore, and Hualien**, predicts the next 7 days using
linear regression, and updates the results daily via GitHub Actions.

## Outputs
- `air_quality_live_multi.csv` – Latest live AQI data
- `kaggle_forecast.csv` – 7-day forecast based on Kaggle data
- `per_city_forecast.csv` – Per-city trend predictions

## Automation
Runs daily at **03:00 UTC** using GitHub Actions.

##  Author
**Shwetha S A
