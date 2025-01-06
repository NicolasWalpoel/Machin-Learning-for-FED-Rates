# Machin-Learning-for-FED-Rates

This project is part of the course Machine learning for portfolio management and trading dispensed by Sylvain Champonnois (CFM) at ENSAE Paris.

The aim of this work is to create a Machin Learning model for rates predictions. We've computed a light GBM and a Random Forest each in separated branchs of the repository but using the same input made avaible in the project.

In the main branch of the project, we introduced methods for rate prediction, including the linear model and the Taylor Rule. While the Taylor Rule is a reliable predictor, its limitations highlight the need for updates and enhancements, such as incorporating machine learning. The Federal Reserve itself suggests adapting policy rules to evolving economic paradigms, emphasizing the importance of flexible, modern approaches.

The second part of this work implements a LightGBM model using the FRED database for rate predictions. This model, optimized with restrictive hyperparameters, delivers accurate estimations without overfitting and outperforms traditional methods like the Taylor Rule during the test period (2010-2018), though it does not exceed the most advanced criteria.

To go further, I would recommend developing a second text-based approach using NLP techniques to process the FED’s decision papers. One could also incorporate sentiment analysis from major market participants, for instance, by analyzing tweets. If interested, I have worked on a project scraping Twitter data using the API: Binance_trade_automatization (10). I've also made avaible a scrapping function for yfinance data since in the main project I've use the 13 week bonds Index (Tickers ^IRX) as a tradable asset and created several trading strategies using the predictions (this last part will be avaible soon). 
