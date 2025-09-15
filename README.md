# Project Summary

This project, completed as a Stats 411 final report, investigates Meta Platforms (Facebook) stock price trends from 2014 to 2023 using multivariate statistical analysis. The dataset contained 2,516 observations and 20 variables, including daily price movements, trading volume, and technical indicators such as RSI, CCI, moving averages, MACD, Bollinger bands, and volatility measures

## Baseline Analysis
The team conducted a Principal Component Analysis (PCA) on the full dataset, finding that the first two principal components explained over 80% of the variance. This suggested that stock movements are highly influenced by correlated price and moving average variables. Factor Analysis with two factors grouped most technical indicators together while separating volatility and momentum indicators, capturing about 80% of cumulative variance. A Canonical Correlation Analysis (CCA) then linked technical indicators with next-day close prices and volumes, showing strong predictive relationships between moving averages, Bollinger bands, and subsequent market outcomes

## Subset Analysis

The dataset was then reduced to focus on long-term indicators such as RSI(14), CCI(14), moving averages, MACD, Bollinger bands, and volatility measures. PCA again showed that the first two components captured nearly 80% of the variance. Factor analysis with three factors grouped moving averages and Bollinger bands together, momentum indicators separately, and volatility measures distinctly. Canonical correlation confirmed the relationships between these factors and next-day prices and volumes, reinforcing the importance of both trend-following and volatility indicators

## Key Insight

Overall, the project demonstrated that Meta’s stock price trends are strongly tied to technical indicators, especially moving averages and volatility measures. Multivariate methods such as PCA, factor analysis, and CCA provided complementary insights, with PCA reducing dimensionality, factor analysis revealing latent structures, and CCA highlighting predictive relationships for forecasting next-day performance.
