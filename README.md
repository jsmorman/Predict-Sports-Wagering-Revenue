Predict Sports Wagering Revenue

Problem Statement
The State Legislature of Connecticut is reviewing a bill to legalize sports wagering within the state. The State Legislature must carefully weigh pros and cons when deciding pass or reject the bill. If they pass the bill, the bill moves on to the Sentate for final approval. If the Senate approves, Connecticut would become the 12th state in the United States where sports wagering has been legalized.

A major consideration by the State Legislature is the potential revenue gain in the State General fund. All sources of gaming share revenue with the state and make transfers into the State General fund at the end of the fiscal year. While sports wagering itsself is likely to bring in new revenue for the state, the state must consider reductions in other revenue streams that the new sports wagering revenue stream may cause.

Using West Virginia has a protype, we will build a SARIMAX time series model that will predict tax revenue for one year, broken down on a weekly basis. After modeling, we will use mean squared error to measure the model's succes. Our goal is to provide the state with a model that can predict tax revenue as closely as possible, giving the state more confidence to make their decision.



Sources:

West Virginia Sports Wagering Reports:
https://wvlottery.com/secured-portal-reporting/?hash=5be9f594

How to Grid Search SARIMA Hyperparameters for Time Series Forecasting
Jason Brownlee
https://machinelearningmastery.com/how-to-grid-search-sarima-model-hyperparameters-for-time-series-forecasting-in-python/

2019 NFL Season Schedule:
https://www.pro-football-reference.com/years/2019/games.htm

2019-2020 NBA Season Schedule:
https://www.basketball-reference.com/leagues/NBA_2020_games.html

2019 MLB Schedule:
https://www.baseball-reference.com/leagues/MLB/2019-schedule.shtml