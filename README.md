# Markowitzs_modern_portfolio_theory.
The modern portfolio theory (MPT) is a practical method for selecting investments in order to maximize their overall returns within an acceptable level of risk. This mathematical framework is used to build a portfolio of investments that maximize the amount of expected return for the collective given level of risk.

American economist Harry Markowitz pioneered this theory in his paper "Portfolio Selection," which was published in the Journal of Finance in 1952.He was later awarded a Nobel Prize for his work on modern portfolio theory.

Markowitz's Modern Portfolio Theory (MPT), developed by Harry Markowitz in 1952, is a fundamental concept in the field of finance and investment. It provides a framework for constructing an investment portfolio that aims to achieve the optimal trade-off between risk and return. The key idea behind MPT is diversification, which involves spreading investments across different assets to reduce risk without sacrificing returns.

Here are the main components and principles of Markowitz's Modern Portfolio Theory:

1. **Asset Selection:**
   - MPT starts with a set of available assets or investments. These assets can include stocks, bonds, real estate, and other financial instruments.

2. **Expected Return:**
   - For each asset in the portfolio, investors estimate the expected return. The expected return represents the mean or average return that an asset is expected to generate in the future.

3. **Risk (Variance):**
   - MPT quantifies risk as the variance or standard deviation of an asset's returns. A lower standard deviation indicates lower risk, while a higher standard deviation implies higher risk.

4. **Covariance and Correlation:**
   - MPT also considers the relationship between the returns of different assets. The covariance and correlation coefficients help measure how assets move in relation to each other. Negative correlations can help reduce portfolio risk.

5. **Efficient Frontier:**
   - The efficient frontier is a graphical representation of all possible portfolios that maximize expected return for a given level of risk (or minimize risk for a given level of return). Portfolios on the efficient frontier are considered optimal because they provide the best risk-return trade-off.

6. **Portfolio Diversification:**
   - MPT encourages diversification, which means combining assets with different risk-return profiles in a portfolio. Diversification can reduce overall portfolio risk without significantly sacrificing expected return.

7. **Risk-Free Asset:**
   - MPT introduces a risk-free asset, typically represented by government bonds. The risk-free rate is the return investors can earn with no risk. It serves as a baseline for comparing the performance of risky portfolios.

8. **Capital Market Line (CML):**
   - The Capital Market Line represents a combination of the risk-free asset and a risky portfolio on the efficient frontier. It shows the optimal trade-off between risk and return for an investor with various risk preferences.

9. **Tangency Portfolio (Market Portfolio):**
   - The point where the Capital Market Line (CML) is tangent to the efficient frontier is known as the Tangency Portfolio or Market Portfolio. This portfolio represents the optimal combination of risky assets and the risk-free asset for a given level of risk aversion.

10. **Asset Allocation:**
    - Investors can select their desired level of risk by adjusting the allocation of assets between the risky portfolio (based on the efficient frontier) and the risk-free asset. This allocation is known as the optimal asset allocation.

11. **Sharpe Ratio:**
    - The Sharpe ratio measures the excess return (return above the risk-free rate) per unit of risk (standard deviation). It helps investors evaluate the risk-adjusted performance of their portfolios.

Markowitz's Modern Portfolio Theory has been foundational in the field of finance and has influenced the development of various portfolio optimization techniques and risk management strategies. Investors use MPT principles to build diversified portfolios that align with their risk tolerance and investment goals.

# PROJECT MOTIVATION

This project is meant to answer this question

WHAT IS THE OPTIMAL COMBINATION OF INVESTMENT PORTFOLIO IN S&P 500?

# DATA UNDERSTANDING 

There is only one dataset used in this project and it was downloaded from yahoo finance library on python

# LIBRARIES USED

The following libraries were used to excute this project

> 1. Numpy

> 2. Pandas

> 3. Matplotlib

> 4. yfinance

> 5. Scipy

## Installations
This libraries work in latest python and they can be installed by running this code

> 1. pip install numpy

> 2. pip install pandas

> 3. pip install yfinance

> 4. pip install Scipy
  
# SUMMARY OF RESULT

The optimization process has determined that the portfolio with 100% allocation to Cisco Systems (CSCO) is the optimal choice based on the given input data and constraints. However, it's essential to interpret these results in the context of your specific objectives and constraints. A portfolio heavily concentrated in a single asset may have higher risk, and your investment strategy should align with your risk tolerance and financial goals. Additionally, these results are based on historical data and assumptions, and real-world investing involves various factors and uncertainties.

In-Sample Performance Metrics:

Sharpe Ratio (In-Sample):
Sharpe Ratio measures the risk-adjusted return of a portfolio. A higher Sharpe Ratio indicates better risk-adjusted performance. In your in-sample data, the Sharpe Ratio is approximately -0.1935. A negative Sharpe Ratio suggests that, in the in-sample period, the portfolio didn't generate a positive risk-adjusted return. It indicates that the portfolio's return was not sufficient to compensate for the level of risk taken.
Overall, based on the provided metrics, the portfolio strategy did not perform well in either the in-sample or out-of-sample datasets. The negative Sharpe and Sortino Ratios suggest that the portfolio did not generate sufficient returns relative to the level of risk it carried. Additionally, the substantial Maximum Drawdown values indicate significant losses.

It's essential to consider these results in the context of your specific investment goals and constraints. Negative performance metrics like these may warrant a reevaluation of the portfolio strategy or further optimization. Additionally, other factors such as transaction costs and market conditions should be taken into account for a comprehensive assessment.

