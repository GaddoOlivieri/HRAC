# HRAC

## Active production model

The active Coin In forecasting model is stored in
`active_xgboost_model/coin_in_model.joblib`.

It is an XGBoost regression model with EIA Central Atlantic gas prices, trained
on data from January 1, 2023 through September 22, 2026. Model provenance,
validation metrics, and forecast policy are recorded in
`active_xgboost_model/model_report.json`.

## Total CoinIn XGBoost Gas Model

The Total Coin In production model is stored in
`total_coin_in_xgboost_gas_model/coin_in_model.joblib`. It uses the same
XGBoost configuration and EIA Central Atlantic gas-price policy as the active
model and is trained through August 31, 2026.

Its point-in-time backtest metrics and model provenance are recorded in
`total_coin_in_xgboost_gas_model/model_report.json`.
