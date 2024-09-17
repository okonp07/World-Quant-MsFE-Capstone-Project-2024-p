# World-Quant-MsFE-Capstone-Project-2024-p
# Machine Learning-Based Swing Trading Strategy for Cryptocurrencies

## Project Overview

**Title**: The Development and Evaluation of a Machine Learning-Based Swing Trading Strategy for Cryptocurrencies

This project aims to design and develop a machine learning-based swing trading strategy for cryptocurrencies, particularly focusing on short- to medium-term price movements. The volatile and unpredictable nature of cryptocurrency markets demands an advanced approach to price forecasting, integrating technical indicators, sentiment analysis, and macroeconomic data.

The primary goal is to develop a strategy that not only predicts price movements effectively but also outperforms traditional methods like buy-and-hold. Additionally, the project evaluates the performance of the strategy using key financial metrics such as the Sharpe Ratio, Sortino Ratio, and Maximum Drawdown.

---

## Objectives of the Study

### Primary Objective:
- To design and develop a swing trading strategy for selected cryptocurrencies using machine learning models.

### Secondary Objectives:
1. To assess if machine learning models are reliable predictors of short- and medium-term price movements.
2. To compare the proposed strategy against conventional swing trading methods and buy-and-hold strategies.
3. To analyze the impact of market volatility, news sentiment, and macroeconomic indicators on the strategy's performance.

---

## Data Collection and Feature Engineering

The data used for this project is collected at various intervals, including hourly, daily, and monthly frequencies. The following key data sources are utilized:
- **Cryptocurrency Price Data**: Historical data for selected cryptocurrencies such as Bitcoin (BTC).
- **Technical Indicators**: 
  - **Relative Strength Index (RSI)**
  - **Bollinger Bands**
  - **Moving Average Convergence Divergence (MACD)**
- **Sentiment Analysis**: Extracted from social media platforms like Twitter and news outlets.
- **Macroeconomic Indicators**: Data from the Federal Reserve Economic Data (FRED), such as interest rates, inflation rates, and commodity prices.

The feature engineering process includes creating time-series data, applying technical indicators, and sentiment scores, all of which will be used as input features for the machine learning models.

---

## Machine Learning Models

The following machine learning models are employed to predict short- to medium-term price movements:
1. **Random Forest (RF)**
2. **Support Vector Machines (SVM)**
3. **Neural Networks (NN)**
4. **Long and short Term Memory (LSTM)**

### Model Validation
- **Time-Series Cross-Validation**: The models are trained and validated using time-series cross-validation to ensure robustness and prevent data leakage.
- **Hyperparameter Tuning**: Various techniques like grid search and random search are applied to optimize model performance.

---

## Backtesting and Evaluation

The strategy's performance is backtested using historical price data of selected cryptocurrencies. Backtesting ensures the strategy is evaluated across different market conditions, including bull and bear markets.

### Performance Metrics:
- **Sharpe Ratio**: Measures risk-adjusted returns.
- **Sortino Ratio**: Focuses on downside risk.
- **Maximum Drawdown**: Assesses the largest peak-to-trough decline in the portfolio.

These metrics are used to compare the machine learning-based strategy against traditional strategies like buy-and-hold.

---

## Tools and Libraries

The project relies on a combination of data science and financial engineering libraries. Key tools include:

- **Python**
  - `pandas`, `numpy`: For data manipulation and analysis.
  - `sklearn`: For implementing machine learning algorithms.
  - `statsmodels`: For time-series analysis.
  - `matplotlib`, `seaborn`: For data visualization.
  - `TA-Lib`: For calculating technical indicators.
  - `backtrader`: For backtesting trading strategies.
- **Data Sources**
  - Cryptocurrency price data from sources like Yahoo Finance or Binance API.
  - Sentiment data from Twitter and news outlets using APIs like `Tweepy` and `NewsAPI`.
  - Macroeconomic data from **FRED**.

---

## Project Workflow

1. **Data Collection**: Acquire historical data on cryptocurrency prices, technical indicators, sentiment analysis, and macroeconomic indicators.
2. **Feature Engineering**: Create features using technical indicators, sentiment scores, and macroeconomic factors.
3. **Model Development**: Train machine learning models (Random Forest, SVM, Neural Networks) on the engineered features.
4. **Backtesting**: Test the trading strategy using historical price data and evaluate its performance using key financial metrics.
5. **Evaluation**: Compare the machine learning strategy's performance to traditional swing trading and buy-and-hold strategies.
6. **Optimization**: Refine the model using cross-validation and hyperparameter tuning.

---

## Results and Discussion

After the development and backtesting of the trading strategy, the results are analyzed to determine:
1. Whether the machine learning models were able to predict short- to medium-term price movements effectively.
2. If the proposed strategy outperforms conventional methods such as buy-and-hold.
3. How market volatility, sentiment, and macroeconomic indicators impact the performance of the trading strategy.

---

## Conclusion

The capstone project provides valuable insights into the application of machine learning in developing swing trading strategies for cryptocurrencies. It contributes to the growing field of financial engineering by exploring how technical, sentiment, and macroeconomic indicators can be leveraged to create robust and predictive trading models.

---

## Installation and Setup

To set up this project on your local machine:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/crypto-swing-trading.git
    cd crypto-swing-trading
    ```

2. Install dependencies using `pip`:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the analysis script:
    ```bash
    python main.py
    ```

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact

For any questions or contributions, feel free to reach out:
- **Email**: okonp07@gmail.com
-          : paidamoyomutepfa@gmail.com
-          : fracksonmakwangwala@gmail.com
- **GitHub**: [https://github.com/okonp07](https://github.com/okonp07)


