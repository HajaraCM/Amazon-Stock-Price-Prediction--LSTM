## Diving Into LSTM for Stock Price Predictions: The Amazon Forecast Experiment

## Overview

This project explores the use of Long Short-Term Memory (LSTM) networks for predicting stock prices. Specifically, the experiment focuses on forecasting Amazon's stock price over a 30-day period and analyzing key market trends using moving averages.

## Why LSTM?

LSTM networks are a powerful tool for time series forecasting, especially for complex datasets like stock prices. Unlike traditional models (e.g., ARIMA, ARMA, Prophet), LSTMs can capture:

Complex Patterns: Recognize intricate relationships in data.

Long-Term Dependencies: Leverage historical trends beyond the recent past.

These capabilities make LSTM ideal for understanding and predicting stock price movements.

## Key Features

* **Model**: LSTM (Long Short-Term Memory)

* **Forecast**: 30-day prediction of Amazon’s stock price

* **Additional Analysis**:

  - 100-day moving average

  - 200-day moving average

* **Outcome**: Accurate predictions aligned with market trends, offering valuable insights into price movements.

## Dataset

The dataset includes historical stock prices of Amazon, with the following fields:

* Date

* Open

* High

* Low

* Close

* Volume

The data was preprocessed to:

* Normalize values for better model performance.

* Smooth out noise using moving averages.

## Workflow

* **Data Preprocessing**:

   - Normalize stock price data.
   - Compute 100-day and 200-day moving averages.

* **Model Architecture**:

   - LSTM layers with dropout for regularization.

   - Fully connected dense layer for predictions.

* **Training and Evaluation**:

  - Train the model on historical stock price data.

  - Evaluate prediction accuracy using Mean Squared Error (MSE).

* **Visualization**:

  - Plot actual vs predicted prices.

  - Highlight trends using moving averages.

## Results

**Predictions**

* The 30-day forecast closely aligned with Amazon’s market trends.

* LSTM demonstrated the ability to anticipate price movements effectively.
  
**Moving Averages** 

* 100-day Moving Average: Smoothed out short-term fluctuations.

* 200-day Moving Average: Highlighted long-term trends.

**Sample Output Plot**

The graph below showcases actual vs predicted stock prices with moving averages:



## Key Takeaways

* Advanced Techniques: LSTM outperforms traditional time series models in identifying long-term dependencies.
  
* Market Trends: Combining LSTM with moving averages provides a holistic view of stock behavior.

* Predictive Insights: While not perfect, LSTM delivers valuable insights into potential price movements.

## Future Enhancements

* Include other technical indicators (e.g., RSI, Bollinger Bands).

* Extend the model to handle multi-stock datasets.

* Experiment with attention mechanisms to further improve accuracy.

## License

This project is licensed under the MIT License.

## Acknowledgements

* TensorFlow/Keras for providing deep learning frameworks.

* Financial datasets for historical stock prices.

* Moving average analysis for enhancing predictions.
