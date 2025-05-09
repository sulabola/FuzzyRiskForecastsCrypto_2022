# Comparison of Fuzzy Risk Forecast Intervals for Cryptocurrencies

Data-driven volatility models and neuro-volatility models have the potential to revolutionize the area of Computational Finance. Many commonly used risk forecasting models do not take into account the uncertainty associated with the volatility of an underlying asset to obtain the risk forecasts. Some tools from the fuzzy set theory can be incorporated into the forecasting models to account for this uncertainty. Interest in the use of hybrid models for fuzzy volatility forecasts is growing. However, a major drawback is that the fuzzy coefficient hybrid models used in fuzzy volatility forecasts are not data-driven. This study uses fuzzy set theory with data-driven volatility and data-driven neuro-volatility forecasts to study the fuzzy risk forecasts. The study focuses on long-term volatility forecasts with daily price data while briefly exploring forecasting models under more granular data as an avenue for future research.

The PDF copy of the paper can be downloaded from here: [Download Paper](https://ieeexplore.ieee.org/abstract/document/9776213) 

A preprint version of the paper is available in the repository.

Programming Language: [R](https://cran.r-project.org/bin/windows/base/) / [RStudio](https://posit.co/downloads/)

Data: The provided R codes download data directly from [Yahoo!Finance](https://ca.finance.yahoo.com/)

### Findings

In this work, we obtained the forecasts of Value at Risk (VaR) and Expected Shortfall (ES) for the top six cryptocurrencies by market capitalization. We used both the traditional time series models as well as relatively recent data-driven, regularized, and neuro-volatility methods to get the volatility forecasts. We also compare the stability of our forecasts using the Model Risk metric. 
Also, to compare the quality of forecasts between data-driven and neuro-volatility models, we obtain fuzzy confidence intervals for the forecasts using a trapezoidal membership function. The narrower fuzzy intervals imply a better forecast quality. We observed that the data-driven models produced better forecasts for cryptocurrencies, while for the regular stocks and indexes, the neuro-volatility model gave better forecasts. Also, the data-driven models are much more efficient in terms of computational complexity, as the running time of the neuro-volatility model is significantly higher than that of the data-driven model.

### References

1. R. J. Hyndman and G. Athanasopoulos, Forecasting: principles and practice, 3rd edition, OTexts: Melbourne, Australia. OTexts.com/fpp3, 2021.
2. Thavaneswaran, A., Paseka, A., \& Frank, J. (2020). Generalized value at risk forecasting. Communications in Statistics-Theory and Methods, 49(20), 4988-4995.


