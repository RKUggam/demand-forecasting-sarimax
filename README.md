## Demand Forecasting using SARIMAX

### Problem Statement
Forecast daily order demand to support operational planning and resource allocation.

### Dataset
Historical order-level data aggregated to daily demand.

### Approach
- Exploratory Data Analysis
- Time Series Decomposition
- Stationarity Testing (ADF)
- Baseline ARIMA Modeling
- SARIMAX Optimization
- Model Evaluation using MAE and RMSE
- Business Insights and Recommendations

### Final Model
SARIMAX model selected based on superior out-of-sample performance.

### Results
- MAE ≈ 47.6
- RMSE ≈ 62.5

### Business Impact
Forecasts enable staffing, inventory, and logistics planning with acceptable error margins.

### Future Work
- Add promotions, holidays, weather as exogenous variables
- Hierarchical forecasting
- ML model benchmarking
