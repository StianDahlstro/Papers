# Papers
Various public papers, mostly from Arxiv og SSRN

Abstracts from the papers and where to find them in alphabetical order:

- An Introduction to Arbitrage Trading Strategies
  - Arbitrage trading strategies are a class of trading strategies that involve buying and selling financial instruments to take advantage of price discrepancies. The goal of arbitrage trading is to make a profit from the differences in prices between securities or markets, without taking on significant directional risk. Arbitrage trading strategies typically rely on quantitative analysis and mathematical models to identify mispricing and execute trades quickly before the market adjusts. In this article, we will introduce five popular arbitrage trading strategies and provide a simple example and reference materials for each strategy.
  - The paper can be found on SSRN [here](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4420232) or  in this repo [here](AnIntroductionToArbitrageTradingStrategies.pdf).

- Automated Market Making and Arbitrage Profits in the Presence of Fees
  - We consider the impact of trading fees on the profits of arbitrageurs trading against an
automated marker marker (AMM) or, equivalently, on the adverse selection incurred by liquidity
providers due to arbitrage. We extend the model of Milionis et al. [2022] for a general class
of two asset AMMs to both introduce fees and discrete Poisson block generation times. In our
setting, we are able to compute the expected instantaneous rate of arbitrage profit in closed
form. When the fees are low, in the fast block asymptotic regime, the impact of fees takes a
particularly simple form: fees simply scale down arbitrage profits by the fraction of time that
an arriving arbitrageur finds a profitable trade.
  - The paper can be found on one of the authors' [own website](https://moallemi.com/ciamac/research-interests.php) or in this repo [here](AutomatedMarketMakingAndArbitrageProfitsInThePresenceOfFees.pdf).

- Automated Volatility Forecasting
  - We develop an automated system to forecast volatility by leveraging over one hundred features and five machine learning algorithms. Considering the universe of S&P 100 stocks, our system results in superior out-of-sample volatility forecasts compared to existing risk models across forecast horizons. We further demonstrate that our system remains robust to different specifications and is scalable to a broader S&P 500 stock universe via hyperparameter transfer learning. Finally, the statistical improvement in volatility forecasts translates into an enhanced annual return around 8.5% from a cross-sectional variance risk premium strategy.
  - The paper can be found on SSRN [here](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3776915) or in this repo [heer](AutomatedVolatilityForecasting.pdf).

- Copula-Based Trading of Cointegrated Cryptocurrency Pairs
  - This research introduces a novel pairs trading strategy based on copulas for cointegrated pairs of cryptocurrencies. To identify the most suitable pairs, the study employs linear and non-linear cointegration tests along with a correlation coefficient measure and fits different copula families to generate trading signals formulated from a reference asset for analyzing the mispricing index. The strategy's performance is then evaluated by conducting back-testing for various triggers of opening positions, assessing its returns and risks. The findings indicate that the proposed method outperforms buy-and-hold trading strategies in terms of both profitability and risk-adjusted returns.
  - The paper can be found on Arxiv [here](https://arxiv.org/abs/2305.06961) or in this repo [here](CopulaBasedTradingOfCointegratedCryptocurrencyPairs.pdf).

- Empirical Determinants of Momentum: A Perspective From International Data
  - We use out-of-sample international data to consider U.S.-based empirical proxies for momentum explanations. We find that the proxy for the hypothesis that investor underreaction to information arriving in small bits rather than in large chunks results in momentum receives reliable support internationally. The market/book ratio as a proxy for valuation uncertainty, and potentially for investor overconfidence as well, receives secondary support, but we find no support for real options proxies. We confirm out-of-sample that momentum is stronger in up-markets and less-volatile markets; these market states represent high investor confidence in the original studies.
  - The paper can be found on SSRN [here](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4012902) or in this repo [here](EmpiricalDeterminantsOfMomentum.pdf).

- Evaluation of Dynamic Cointegration-Based Pairs Trading Strategy in the Cryptocurrency Market
  - This research aims to demonstrate a dynamic cointegration-based pairs trading strategy, including an optimal look-back window framework in the cryptocurrency market, and evaluate its return and risk by applying three different scenarios. We employ the Engle-Granger methodology, the Kapetanios-Snell-Shin (KSS) test, and the Johansen test as cointegration tests in different scenarios. We calibrate the mean-reversion speed of the Ornstein-Uhlenbeck process to obtain the half-life used for the asset selection phase and look-back window estimation. By considering the main limitations in the market microstructure, our strategy exceeds the naive buy-and-hold approach in the Bitmex exchange. Another significant finding is that we implement a numerous collection of cryptocurrency coins to formulate the model's spread, which improves the risk-adjusted profitability of the pairs trading strategy. Besides, the strategy's maximum drawdown level is reasonably low, which makes it useful to be deployed. The results also indicate that a class of coins has better potential arbitrage opportunities than others. This research has some noticeable advantages, making it stand out from similar studies in the cryptocurrency market. First is the accuracy of data in which minute-binned data create the signals in the formation period. Besides, to backtest the strategy during the trading period, we simulate the trading signals using best bid/ask quotes and market trades. We exclusively take the order execution into account when the asset size is already available at its quoted price (with one or more period gaps after signal generation). This action makes the backtesting much more realistic.
  - The paper can be found on Arxiv [here](https://arxiv.org/abs/2109.10662) or in this repo [here](EvaluationOfDynamicCointegrationBasedPairsTradingStrategyInTheCryptocurrencyMarket.pdf).
