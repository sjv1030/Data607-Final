# Data607-Final
Final Project

Betting Against Beta in the S&P 500

BACKGROUND:

In most standard Finance 101 courses, students are taught that the higher the risk, the higher the reward (i.e., only take on more risk, if reward increases as well). This ideology is ingrained in many theories, most notably in the Capital Asset Pricing Model where the return of a stock is linearly associated to the risk sensitivity (i.e., beta) to the broader equity market (e.g., S&P 500). As a result, individuals that aren't risk averse and wanted higher returns, ended up taking on more risk in their portfolio by selecting risker (higher beta) stocks.

However, in 2010, Andrea Frazzini and Lasse H. Pedersen published a paper titled "Betting Against Beta" (http://www.nber.org/papers/w16601) where they show empirically that lower beta stocks (less risky stocks) actually outperform higher beta stocks (higher risky stocks).

Many investors have been able to reproduce similar results and some have even launched investment funds following this methodology.

This code attempts to reproduce the study. However, due to various data limitations and difference in beta calculation, this attempt doesn't result in the same conclusion.

DATA:

Most of the data are sourced via Quantmod or CSV file on this GitHub. However, there is a large zip file with daily prices for a large number of stocks downloaded from [Quandl.com](https://www.Quandl.com). The only way to ensure 100% complete reproducibility of this project is to make this large zip file available via my [Dropbox](https://www.dropbox.com/sh/fzih0uypabr2a99/AAA_i1aa5XG1NpAQIttH2Tdna?dl=0). This file needs to be downloaded and extracted. The CSV that will be extracted is about 1.8gbs. This CSV should be extracted in the folder you'll ultimately set as your working directory and rename the CSV file to "WIKI_PRICES_ALL.csv".
