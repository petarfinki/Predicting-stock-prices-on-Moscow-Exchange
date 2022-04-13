# Predicting stock prices on Moscow Exchange

## Project Introduction
Machine learning in finance is now considered a key aspect of several financial services and applications, including managing assets, evaluating levels of risk, calculating credit scores, and even approving loans. ML tends to be more accurate in drawing insights and making predictions when large volumes of data are fed into the system. Investors need to understand the nature of individual stocks and their dependence factors that effect to stock prices in order to increase their chances of achieving higher returns. But all these, the investors require to make effective investment decisions at the right time using an accurate and appropriate amount of information.

A stock index is a representative of a group of stocks’ prices. This index is computed from the prices of defined stocks and its change can reflect the overall performance of the stocks listed in the index. In particular, a stock index is a weighted average market value of a number of firms compared with the value on the base trading day. 

In this project, I am working with *[Moscow Exchange stock index](https://uk.finance.yahoo.com/quote/IMOEX.ME?p=IMOEX.ME)* which tracks the performance of the 50 largest and most liquid Russian companies from 10 main economy sectors, listed on The Moscow Stock Exchange. Historically, the MOEX Russia Index reached an all time high of 4292.68 in October of 2021 and now as the sanctions hit the domestic economy, stock prices are in a free fall with banks and oil companies among the biggest losers.

I am using data from the python library yfinance, to access the financial and daily updated data available on Yahoo Finance. To predict stock prices based on this information, I was focused on building deep learning models and LSTM with the Keras library in Python.

## Project Flow
1. Data preprocessing and cleaning
2. Data transformation
3. Feature extraction
4. Visualization and prediction
5. Conclusion

## Future work
Investing on the stock markets have been of interest to many investors around the world. However, making a decision is a complex task as numerous factors are involved. For successful investment, investors are keen to forecast the future situation of the stock market. Even small improvements in predictive efficiency can be very profitable. In addition to the historical prices, other information might have effect to the stock such as politics, economic growth, financial news and social media. Many studies have proven that the sentiment analysis has a high impact on future prices. Thus, a mix of technical and fundamental analyses could produce the prediction more efficient and would be interesting to be added in to the state-of-the-art ML as future works. 

This was the decisive factor why I was determined to develop a project with Russian economy involved. The stock market rally reflects in part investor bets that uncertainty from the conflict will make central banks move more cautiously to raise interest rates. 

## References
- [MOEX Russian Index](https://tradingeconomics.com/russia/stock-market)
- [A Survey on Machine Learning for Stock Price Prediction: Algorithms and Techniques](https://www.scitepress.org/Papers/2020/93407/93407.pdf) 
- [LSTM neural network algorithm](https://machinelearningmastery.com/gentle-introduction-long-short-term-memory-networks-experts/)

*Petar Dimitrievski 13.04.2022*
