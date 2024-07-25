# Home LLC Assignment
**Check this `LLCnotebook.ipynb`**

## Overview

In this assignment, we analyze 20 years of data on US housing prices. The data was sourced from the following platforms:

- [Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org/)
- [OECD](https://www.oecd.org/en.html)
- [World Bank](https://data.worldbank.org/)

## Approach

1. **Correlation Analysis**: 
   We started by examining the correlation between the S&P Home Price Index and various other factors. This helped us identify the most relevant variables affecting housing prices.

2. **Data Cleaning and Feature Selection**: 
   Based on the correlation analysis, we cleaned the data and selected the factors with high correlations for further analysis.

3. **Modeling**:
   - **Initial Attempt**: We initially used Multiple Linear Regression, but the results were unsatisfactory with a highly negative R-squared value.
   - **Refinement**: We switched to Ordinary Least Squares (OLS) Regression. The OLS model significantly improved the fit, achieving an R-squared value of approximately 0.95, indicating a much better performance.
  
## Files
Details about each data file can be found in units.txt file. 

## Summary

The final OLS Regression model provides a robust fit for the housing price data, demonstrating a strong explanatory power with an R-squared value of around 0.95. This reflects a successful analysis and modeling approach, significantly improving over the initial linear regression attempt.



