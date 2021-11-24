# Causability

## Time Series Analysis on Historical IBM Stock Data
International Business Machines Corporation (IBM) is an American multinational technology
company based in New York and founded in 1911, with operations in over 170 countries. In
addition to providing integrated solutions and services, IBM also produces and sells computer
hardware, middleware, data platform software.

**Data:** The present study uses the stock market dataset obtained through Kaggle where each
stock contains common features such as: date, opening, high, low, close, adjusted close, and
volume. For the purpose of the study, the IBM stock was used, specifically the closing prices
from 2019 to 2020.

**Problem Statement:**
The goals of the study are (1) identify a possible model for IBM dataset and (2) forecast future IBM stock prices.

**Conclusion:**
It can be concluded that the predicted values using the ARIMA model is not perfect which,
intuitively, makes sense because how can we use one single stock’s historical data to predict its
future prices. If this were the case and if predicting stock prices were so simple, we would all be
rich. It may be important to consider that the price of a stock may possibly be affected by another
stock throughout time and casual discovery allows us to do so.

## Application in Causal Discovery
**Data:**
 For the purpose of the application, stocks of various big-tech corporations are analyzed
and used such as IBM, Amazon, Google, Apple, Yahoo, Netflix, Facebook, Oracle, DOW, and
NASDAQ.

**Problem Statement:**
The goal of the application is to determine whether or not stocks can affect
one another through time.

**Background:**
Causal discovery aims to reconstruct the underlying causal dependencies and/or
relationships from large-scale time series datasets, accounting for both linear and nonlinear
relationships, along with different time lags. Traditional pairwise correlations that yield spurious
associations where two or more events or variables are associated but not causally related which
is not very informative. Causal discovery, on the other hand, emphasizes in assessing the
significance of causal links and discovering possible linkages between variables.

**Conclusion:**
From the application, it is evident that stocks can, in fact, be affected by other stocks through
time. Using the summary bar charts, we can apply what we discovered through this analysis
toward a real life situation. Given that you are a shareholder or if you have stocks in one of the
above tech corporations. By knowing that Netflix is the most influential stock and Google is the
most susceptible to the effect of Netflix, meaning change whether rise or fall is most likely going
effect Google the most, if you are planning to invest or if you have stock in Google you should
be more aware of the stock market for Netflix.
