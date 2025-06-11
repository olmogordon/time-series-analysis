# Advanced GDP Forecasting System Evaluation Report

Generated on: 2025-05-09 14:19

## Models Evaluated

Number of models: 1
Evaluation period: 2009-06-30 00:00:00 to 2024-09-30 00:00:00
Number of observations: 62

## Statistical Performance Metrics

| Model | RMSE | MAE | R² | Direction Accuracy |
|-------|------|-----|----|-----------------|
| qrf | 1.7048 | 0.7959 | -0.0076 | 0.7049 |

## Economic Value Metrics

| Model | Mean Return | Volatility | Sharpe Ratio | Utility |
|-------|-------------|------------|--------------|--------|
| qrf | 0.6157 | 0.8779 | 0.7013 | -1.3111 |

## Uncertainty Quantification Metrics

| Model | PI Coverage | PI Width | Interval Efficiency |
|-------|-------------|----------|---------------------|
| qrf | 0.5484 | 3.1918 | 0.1718 |

## Feature Importance

### Top 10 Features

- **Unemployment_monthly_Value_diff_mean**: 0.3419
- **GDP_quaterly_Value_raw**: 0.1177
- **Unemployment_monthly_Value_raw_slope**: 0.0613
- **Unemployment_monthly_Value_raw_std**: 0.0491
- **CPI_mon_monthly_Value_raw_mean**: 0.0279
- **Unemployment_monthly_Value_diff_slope**: 0.0275
- **InterestRate_monthly_Value_diff_mean**: 0.0202
- **Unemployment_monthly_Value_diff_std**: 0.0150
- **CPI_mon_monthly_Value_raw_last**: 0.0147
- **InterestRate_monthly_Value_raw_std**: 0.0135

## Conclusion

- Based on **RMSE**, the best performing model is **qrf** with RMSE of 1.7048.
- Based on **directional accuracy**, the best performing model is **qrf** with accuracy of 70.49%.
- Based on **economic utility**, the best performing model is **qrf** with utility of -1.3111.

The **qrf** model outperforms across all metrics and is recommended for GDP forecasting.