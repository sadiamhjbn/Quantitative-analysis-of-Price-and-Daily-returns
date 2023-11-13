**Project Summary: Quantitative Analysis of Price & Daily Returns**

**Objective:**
The project aims to conduct a quantitative analysis of the daily returns of Amazon (AMZN) stock prices from January 1, 2018, to January 1, 2023. The analysis includes descriptive statistics, distribution analysis, hypothesis testing, and the implementation of a simple linear regression model.

**Tools Used:**
- **Python Libraries:**
  - yfinance for downloading historical stock prices.
  - NumPy and Pandas for data manipulation and analysis.
  - Matplotlib and Seaborn for data visualization.
  - scipy.stats for statistical analysis.
  - pandas_datareader for additional data retrieval.

**Key Steps:**

1. **Data Download and Exploration:**
   - Historical stock prices of AMZN were downloaded using the yfinance library.
   - The dataset was explored, and the first few rows were inspected to understand the structure.

2. **Calculation of Daily Returns:**
   - Instantaneous rates of return were calculated using the logarithmic difference of closing prices.
   - The data was cleaned by dropping missing values.

3. **Data Visualization:**
   - Time series plots of daily returns were created to visualize trends.
   - Descriptive statistics, including mean, standard deviation, and quartiles, were computed.

4. **Distribution Analysis:**
   - Kurtosis, skewness, and a histogram were used to analyze the distribution of daily returns.
   - A hypothesis test was conducted to compare the kurtosis of the sample with a normal distribution.

5. **Comparison with a Normal Distribution:**
   - Random numbers following a normal distribution were generated for comparison.
   - Histograms of daily returns and the random normal distribution were plotted together for visual comparison.

6. **Hypothesis Testing:**
   - A t-test was performed to test the null hypothesis that the mean of a sample of daily returns is zero.
   - Results were interpreted in terms of the test statistic and p-value.

7. **Linear Regression Model:**
   - Lagged price values (lags) were created to implement a simple linear regression model.
   - The model was fitted to predict stock prices based on lagged values.
   - The predicted values were plotted against actual stock prices for visual assessment.

**Key Findings:**
- Descriptive statistics indicated a mean daily return of 0.0275% for AMZN.
- The distribution of daily returns showed leptokurtosis, indicating fatter tails and a more peaked central region compared to a normal distribution.
- A hypothesis test confirmed the departure from a normal distribution based on kurtosis.
- The t-test suggested that the mean of the sample is not significantly different from zero.
- The linear regression model provided a visual representation of predicted stock prices based on lagged values.

**Conclusion:**
The project provided a comprehensive quantitative analysis of Amazon's daily stock returns, covering statistical measures, distribution characteristics, hypothesis testing, and a simple linear regression model. These analyses contribute to a better understanding of the underlying patterns and behaviors in the stock's price movements, aiding in informed decision-making for financial strategies and risk management.
