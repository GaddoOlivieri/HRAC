# HRAC

## Active production model

The active Coin In forecasting model is stored in
`active_xgboost_model/coin_in_model.joblib`.

It is an XGBoost regression model with EIA Central Atlantic gas prices, trained
on data from January 1, 2023 through September 22, 2026. Model provenance,
validation metrics, and forecast policy are recorded in
`active_xgboost_model/model_report.json`.
