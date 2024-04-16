# prophet-challenge
Module 8 challenge
## Module 8 Challenge: Prophet Analysis for MercadoLibre Search Trends

### Problem Statement

This project focuses on analyzing Google search traffic data for MercadoLibre, Latin America's largest e-commerce platform. The analysis seeks to answer several key questions:

1. Find unusual patterns in hourly Google search traffic.
2. Mine the search traffic data for seasonality.
3. Relate the search traffic to stock price patterns.
4. Create a time series model with Prophet.
Additionally, the task includes forecasting Google search traffic for the next 80 days using time series modeling techniques.

### Solution Outline

The solution is structured as follows:

1. **Identifying Unusual Patterns in Hourly Google Search Traffic**: Initial analysis involves plotting the search traffic for May 2020, a significant month due to the release of quarterly financial results, which shows increased search activity.
  
2. **Seasonality and Regular Patterns Detection**: This involves detailed analysis across various timescales to identify daily, weekly, and yearly patterns.
  
3. **Correlation Analysis with Stock Price Metrics**: This segment explores the relationship between search traffic dynamics and MercadoLibre's stock price behavior, including price volatility.
  
4. **Time Series Forecasting with Prophet**: Implementation of a forecasting model to predict future search traffic trends.

### Detailed Implementation

#### Analyzing Hourly Search Traffic Patterns
- The data for May 2020 is thoroughly examined to understand deviations from typical traffic patterns, coinciding with MercadoLibre's earnings release.
- Daily and weekly regularities are also noted, with a comparative analysis against median traffic levels to establish the significance of observed spikes.

#### Seasonality Detection in Search Traffic
- Comprehensive plots are generated for daily, weekly, and yearly intervals to capture inherent periodic trends:
  - Daily patterns are discerned by averaging hourly traffic, revealing peak periods around midnight and troughs in early morning hours.
  - Weekly trends show higher traffic mid-week, with a notable dip during weekends.
  - Yearly analysis highlights significant fluctuations with specific attention to holiday periods and other notable weeks.

#### Correlating Search Traffic with Stock Market Dynamics
- Integration of stock price data to assess correlations with search trends, particularly focusing on first-half 2020 due to its economic pertinence.
- Detailed analysis involves creating lagged search trend metrics, calculating stock volatility, and assessing hourly returns to pinpoint any significant correlations.
- Preliminary findings suggest minimal direct correlations, with further statistical analysis indicating only weak potential linkages.

#### Forecasting with Prophet
- A Prophet model is constructed and tuned to reflect the observed seasonalities accurately:
  - The model confirms known daily and weekly traffic patterns and effectively maps broader annual trends.
  - Predictive performance is evaluated by projecting search traffic trends two months ahead, indicating consistency with historical data but with minor deviations that warrant cautious interpretation.

### Conclusion

The analytical journey through MercadoLibre's Google search traffic data provides insightful revelations about temporal search patterns and their weak associations with stock market behavior. While the time series model developed with Prophet adeptly captures and extrapolates known patterns, the forecasting underscores the inherent challenge and uncertainty in predicting search traffic precisely. Further research and more granular data could potentially refine these correlations and enhance predictive accuracy.

### Resources
I relied hevenly on the class room assignments to complet this, I also used askbcs stackoverflow, and in class breakout rooms.
