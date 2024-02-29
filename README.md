# Cross-Dataset Time Series Forecasting using ARIMA and LSTM models

## Introduction

Time series forecasting (TSF) is crucial in data analysis, especially in economic and financial contexts, where the prediction of trends plays a vital role. This project explores the performance of two prominent forecasting methodologies: Auto Regressive Integrated Moving Average (ARIMA) and Long Short-Term Memory (LSTM) models, focusing on economic and financial datasets.

## Motivation

The dynamic nature of recent datasets poses challenges for traditional forecasting models like ARIMA, especially with large non-linear and complex datasets. Deep learning techniques such as LSTM have emerged as promising alternatives for capturing complex sequential dependencies in time series data. However, empirical evidence is lacking, particularly regarding LSTM's performance compared to traditional econometric methods like ARIMA, especially in financial time series forecasting.

## Objectives

- Assess the performance of ARIMA and LSTM models across diverse economic and financial datasets.
- Investigate the potential of combining linear (ARIMA) and non-linear (LSTM) models for more accurate forecasting.
- Address the limitations of individual models by creating a hybrid approach.
- Contribute to advancing forecasting techniques and providing robust predictions across various applications.

## Approach

- **Phase 1: ARIMA Preprocessing**: Utilize ARIMA to identify linear structures in the data and preprocess it to make it stationary.
- **Phase 2: LSTM Modeling**: Employ LSTM to handle preprocessed data, capturing complex non-linear relationships and dependencies.
- **Hybrid Model**: Combine the strengths of ARIMA's linear approach with LSTM's non-linear capabilities to create a comprehensive forecasting model.

## Dataset and Evaluation

The project conducts cross-data set time series forecasting on two diverse datasets: NVIDIA stock prices (NVDA) and Bitcoin to USD exchange rates (BTC-USD). Evaluation metrics include Root Mean Square Error (RMSE), R2 score, Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), and Median Absolute Percentage Error (MDAPE).

## Results and Discussions

- LSTM outperforms ARIMA in terms of RMSE for both datasets.
- LSTM demonstrates superior accuracy and reliability, especially in capturing complex temporal patterns and long-term dependencies in dynamic financial datasets.
- Cross-data set forecasting reveals challenges, with LSTM exhibiting better performance but still facing complexities in predicting values solely based on financial instrument prices.

## Conclusion and Future Work

The study underscores LSTM's superiority in time series forecasting, particularly in financial domains. Future work includes exploring multivariate time series modeling techniques, incorporating relevant features for improved prediction, and enhancing model resilience through dynamic updates and ensemble techniques.

## Acknowledgments

We acknowledge the support and resources provided by University of Essex.

## Authors

- [Rahul Kithalamane Basavaraj]([link-to-author-1-github-profile](https://github.com/RahulKB31))

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

