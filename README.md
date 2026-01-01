Description of the Code Objectives:
This code conducts a comprehensive analysis and empirical comparison of univariate forecasting methods applied to a historical monthly time series: the Industrial Production Index for U.S. electric and gas utilities (FRED series IPG2211A2N, spanning 1939 to approximately 2019–2020).

The main objectives are as follows:
Exploratory Analysis and Preprocessing: Examine stationarity, identify trend and strong seasonality (annual cycles related to energy consumption), and prepare the series for modeling through differencing and decomposition.
Comparison of Forecasting Paradigms: Assess the performance of classical statistical models (SARIMAX), tree-based methods (Random Forest with recursive reduction), interpretable neural models (N-BEATS), attention-based architectures (Temporal Fusion Transformer), and probabilistic deep learning models (DeepAR) over a 12-month forecast horizon.
Objective Evaluation: Compute MSE/RMSE on a held-out test period to determine which approach—traditional, machine learning, or deep learning—best captures the trend, seasonal, and nonlinear patterns of this critical economic series.
Practical Implications: In the energy sector, accurate forecasting of electricity and gas production supports capacity planning, management of seasonal and climate-related risks, and anticipation of industrial demand—particularly important in the context of the energy transition and fluctuating consumption patterns.
