# Statistical-Arbitrage-Portfolio-with-PCA

This is my implementation of the Statistical Arbitrage Portfolio from Dr. Thomas Starke from AAA Quants.

https://github.com/rodler/quantinsti_statarb/blob/master/PCA_2.ipynb

The pairs get downloaded with a chosen granularity from OANDA and are concated into a new pandas dataframe.

The back test is extended in a manner that allows you to print out the current position. Like this, it is possible to get an overview of the current situation and allow you to execute a statistical arbitrage portfolio strategy by hand. The graphic from the back test together with the Z score allow you to find good timing for the market entry!

Instead of relying on a Kalman Filter for the calculation of the dynamic hedge ratio, this model uses the PCA - Principal Component Analysis for this purpose.

It is possible to determine the maximal position for each site with max_pos. Like this, the overall portfolio value gets smoothed out in comparison to Pairs Trading.

In the latest version, a threshold has been added as well as a further improvement. 
