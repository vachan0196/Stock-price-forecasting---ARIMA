# Stock-price-forecasting--(ARIMA)

# Time Series Forecasting

This repository contains the results and documentation of time series forecasting models applied to predict the `Close` price of a given dataset. The models evaluated include ARIMA, rolling window ARIMA, Exponential Smoothing, and ARIMAX with features.

## Summary of Results

### Result 1: Basic ARIMA Model
- **Parameters**: (1, 1, 1)
- **Performance**:
  - Mean Squared Error (MSE): 19140.703341070966
  - Mean Absolute Error (MAE): 106.67970323517373
  - Root Mean Squared Error (RMS): 138.34993075918385

### Result 2: Rolling Window ARIMA Model
- **Parameters**: (1, 1, 1)
- **Rolling Window Size**: 60
- **Performance**:
  - Rolling Mean Squared Error (MSE): 2.1905889209095672
  - Rolling Mean Absolute Error (MAE): 0.8684482220115876
  - Rolling Root Mean Squared Error (RMS): 1.4800638232554593

### Result 3: Exponential Smoothing ARIMA Model
- **Parameters**: (2, 1, 1)
- **Performance**:
  - Combined Mean Squared Error (MSE): 19135.05488278908
  - Combined Mean Absolute Error (MAE): 106.67038416630477
  - Combined Root Mean Squared Error (RMS): 138.32951558792172

### Result 4: Rolling Window Exponential Smoothing Model
- **Parameters**: (2, 1, 1)
- **Rolling Window Size**: 60
- **Performance**:
  - Rolling Mean Squared Error (MSE): 49.957449717587636
  - Rolling Mean Absolute Error (MAE): 1.3988926353117928
  - Rolling Root Mean Squared Error (RMS): 7.068058412151645

### Result 5: ARIMAX Model with Features
- **Parameters**: (1, 1, 1)
- **Performance**:
  - Mean Squared Error (MSE): 6.989611616712787e-06
  - Mean Absolute Error (MAE): 0.002245726825882026
  - Root Mean Squared Error (RMS): 0.0026437873622348652

### Result 6: ARIMAX Model with Features
- **Parameters**: (2, 1, 1)
- **Performance**:
  - Mean Squared Error (MSE): 3.1679223760072346e-05
  - Mean Absolute Error (MAE): 0.005298726212985945
  - Root Mean Squared Error (RMS): 0.005628429955153777

### Result 7: ARIMAX Model with Features
- **Parameters**: (2, 1, 2)
- **Performance**:
  - Mean Squared Error (MSE): 6.713540449360756e-06
  - Mean Absolute Error (MAE): 0.0021928777418972955
  - Root Mean Squared Error (RMS): 0.0025910500669343996

### Result 8: Optimized ARIMA Model
- **Optimal Parameters**: (1, 1, 0)
- **Performance**:
  - Cross-Validated MSE: 0.00028130809752692276
  - Cross-Validated MAE: 0.010195276058380944
  - Cross-Validated RMS: 0.011655879907680494

## Conclusion
The ARIMAX model with parameters (2, 1, 2) and comprehensive feature inclusion has demonstrated the highest accuracy in forecasting the `Close` price. The incorporation of various engineered features significantly enhances the model's performance, making it the best choice among the models tested.

## How to Use
- Clone the repository
- Review the code and results
- Run the provided scripts for your own analysis

