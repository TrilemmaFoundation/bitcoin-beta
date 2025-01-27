# Bitcoin, S&P 500, and Nasdaq-100 Beta Analysis

## Overview
This notebook analyzes the relationship between Bitcoin and the S&P 500, Nasdaq-100 by calculating beta values across different timeframes. The key steps include:

1. **Data Collection**:
   - Retrieves daily historical price data for Bitcoin, S&P 500, and Nasdaq-100.

2. **Data Validation**:
   - Ensures stationarity and absence of autocorrelation in the returns series.

3. **Beta Calculation**:
   - Runs a simple linear regression using returns to calculate beta values for:
     - The entire historical dataset.
     - The past 8 years of data.
     - The post-COVID era (2022 onward).

## Results (as of [January 27, 2025])
- **Bitcoin's beta relative to the S&P 500**:
  - Historical: **0.66**
  - Last 8 years: **0.94**
  - Post-COVID: **1.28**

- **Bitcoin's beta relative to the Nasdaq-100** (representing tech stocks):
  - Historical: **0.56**
  - Last 8 years: **0.78**
  - Post-COVID: **0.94**
