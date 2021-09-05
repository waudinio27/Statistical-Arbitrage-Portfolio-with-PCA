# Statistical-Arbitrage-EUROZONE-with-PCA

This is my implementation of the Simple Pairs Trading Strategy from Dr. Thomas Starke from AAA Quants.

https://github.com/rodler/quantinsti_statarb/blob/master/PCA_2.ipynb

The pairs get downloaded with a choosen granularity from OANDA and are concated into a new pandas dataframe.

The backtest is extended in a manner that allows to print out the actual position. Like this, it is possible to get an overview of the actual situation and allows to execute a statistical arbitrage portfolio strategy by hand. The graphic from the backtest together with the Z score allow to find good positions for the market entry!
