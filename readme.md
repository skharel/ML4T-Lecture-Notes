# GA Tech ML4T - CS 7646 notes

[Syllabus for Fall 2021](http://lucylabs.gatech.edu/ml4t/fall2021/)
[Course home](http://lucylabs.gatech.edu/ml4t/)

# Love the course!

- This is definitely a well done class; take this class before you get into other AI/ML classes. You will learn a lot from here that will make your life easy for other classes.
- You will learn numpy, pandas, data cleaning and visualization in this course

# Lecture video

Lecture is freely available for anyone!

https://omscs.gatech.edu/cs-7646-machine-learning-trading-course-videos

# Notes

## Week 1

Hello Numpy and pandas!

- [Reading and plotting stock data: 1-1.ipynb](./1-1.ipynb)
- [Working with multiple stocks: 1-2.ipynb](./1-2.ipynb)
- [Power of NumPy: 1-3.ipynb](./1-3.ipynb)
- [Statistical analysis of time series: 1-4.ipynb](./1-4.ipynb)

## Week 2

Optimizations

- [Incomplete data: 1-5.ipynb](./1-5.ipynb)
- [Histograms and scatter plots: 1-6.ipynb](./1-6.ipynb)
  - Histograms and scatter plots
  - A closer lok at daily returns
  - What would it look like?
  - Histogram of daily returns
  - How to plot a histogram
  - Computing histogram statistics
  - Compare two histograms
  - Plot two histograms together
  - Scatter plots
  - Fitting a line to data points
  - Slope != correlation
  - Correlation vs slope
  - Scatter plots in python
  - Real world use of kurtosis
- [Sharpe ratio and other portfolio statistics: 1-7.ipynb](./1-7.ipynb)
  - Overview
  - Daily Portfolio values
  - Portfolio Statistics
  - Which portfolio is better?
  - Sharpe Ratio
  - Form of the Sharpe Ratio
  - Computing Sharpie Ratio
- [Optimizers: Building a parameterized model: 1-8.ipynb](./1-8.ipynb)
  - What is an optimizer?
  - Minimization example
  - Minimizer in pythong
  - How to defeat a minimizer
  - Convex Problems
  - Building a parameterized model
  - What is a good error metric?
  - Minimizers finds coefficients
  - Fit a line to given data points
  - And it works for polynomials too!

## Week 3

Intro to ML

- [Optimizers: How to optimize a portfolio: 1-9.ipynb](./1-9.ipynb)

  - What is portfolio optimization
  - The difference optimization can make
  - Which criteria is easiest to solve for?
  - Framing te problem
  - Ranges and constraints

- [How Machine Learning is used at a hedge fund: 3-1.ipynb](./3-1.ipynb)

  - How Machine learning is used at a hedge fund overview
  - The ML problem
  - What's X and Y
  - Supervised Regression Learning
  - How it works with stock data
  - Example at a fintech company
  - Price forecasting demo
  - Backtesting
  - ML tool in use
  - Problems with regression

- [Regression: 3-2.ipynb](./3-2.ipynb)
  - Regression Introduction
  - Parametric Regression
  - K Nearest Neighbor
  - How to predict
  - Kernel Regression
  - Parametric vs Non-parametric
  - Training and testing
  - Example for linear Regression

## Week 4

- [Assessing learning Algorithm: 3-3.ipynb](./3-3.ipynb)
  - Fitting data
  - RMS Error
  - In sample vs out of sample
  - Cross validation, Roll forward cross validation
  - Correlation and RMS Error
  - Overfitting
    <br/>
- [Ensemble learners - bagging and boosting: 3-4.ipynb](./3-4.ipynb)

  - Ensemble
  - Bootstrap aggregating - bagging
  - Overfitting
  - Bagging example
  - Boosting
  - Overfitation

- [Decision Tree & Random forest: 3-5_decision_tree.ipynb](./3-5_decision_tree.ipynb)
  - 2 lecture videos
    - 1st part: what does the tree look like
    - 2nd part: building the tree
      - JR Quinlan's algorithm
      - A Cutler Algorithm
      - Random forest

## Week 5

- [So you want to be a hedge fund manager? 2-1.ipynb](./2-1.ipynb)

  - Types of funds
  - Liquidity and capitalization
  - What type of fund is it?
  - Incentives for fund managers
  - Two and twenty
  - How funds attract investors
  - Hedge fund goals and metrics
  - The computing inside a hedge fund

- [Market Mechanics: 2-2.ipynb](./2-2.ipynb)
  - Market Mechanics Overview
  - What is in an order?
  - The order book
  - Up or down?
  - How orders affect the order book?
  - How orders get to the exchanges
  - How hedge funds exploit market mechanics
  - additional order types
  - Mechanics of short selling: Entry
  - Short Selling
  - Mechanics of short selling: Exit
  - What can go wrong?

## Week 6

- [What is a company worth? 2-3.ipynb](./2-3.ipynb)

  - What is a company worth?
  - Why company value matters?
  - The Balch Bond
  - The value of a future dollar
  - Intrinsic Value
  - Book Value
  - Market Capitalization
  - Why information affects stock price
  - Compute Company value
  - Would buy this stock?

- [The Capital Assets Pricing Model (CAPM): 2-4.ipynb](./2-4.ipynb)
  - The Capital Assets Pricing Model
  - Definition of a portfolio
  - Portfolio return
  - The market portfolio
  - The CAPM Equation
  - Compare alpha and beta
  - CAPM vs active management
  - CAPM for portfolios
  - Implications of CAPM
  - Arbitrage Pricing Theory

## Week 7

- [How hedge funds use the CAPM: 2-5.ipynb](./2-5.ipynb)

  - Risks for hedge funds
  - Two stock scenario
  - Two stock CAPM Math
  - Allocations remove market risk
  - How does it work
  - CAPM for hedge funds Summary

- [Technical Analysis: 2-6.ipynb](./2-6.ipynb)
  - Technical versus fundamental analysis
  - Characteristics
  - Potential indicators
  - When is technical analysis valuable?
  - A few indicators:
    - Momentum
    - Simple Moving Average
    - Bollinger bands
  - Buy or Sell?
  - Normalization

## Week 8

- [Dealing with Data: 2-7.ipynb](./2-7.ipynb)

  - Overview
  - How data is aggregated
  - Price anomaly
  - Stock Splits
  - Split adjustment
  - Dividends
  - Adjusting for Dividends
  - Survivor bias

- [Efficient Markets Hypothesis: 2-8.ipynb](./2-8.ipynb)

  - Our hypothesis
  - EMH hypothesis
  - Origin of Information
  - 3 forms of EMH
  - The EMH Prohibits
  - Is the EMH correct?

- [Market Simulator](./MarketSimulator.ipynb)
  - [Youtube link](https://www.youtube.com/watch?v=TstVUVbu-Tk)

## Week 9

- [Time Series Data](./timeseries_data.ipynb)
- [Vectorize me PPT](./CDB_vectorize_me.pptx)
  - Both are covered in the [youtube video](https://www.youtube.com/watch?v=2e2Yr-Bpo-w)

## [Navigation project](./navigation_project.ipynb)

## [QLearning Trader project overview](./qlearning_Trader_project.ipynb)
