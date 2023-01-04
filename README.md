# File contents
The ipynb files contain the latest execution of code in memory, you can save time by avoiding re-executing them.

The code files are written in Python and Python notebook format (the KeyboardInterrupt error corresponds to interrupting the cell execution process in order to avoid waiting for the complete execution of the code).

The files agent1.py and agent2.py contain the code for training the two DRL agents that have been tested.
The indicators_historical_data file highlights the value of indicators for a given action for testing purposes.
Various financial indicators and ratios are created in a global function in the files alpha101.py, main.py, fin_ratios.py and are grouped in the main.py and all_indicators.py files.

An example of calculating fundamental data can be found in the fundamentals.ipynb file
An example of calculating risk data (CVaR, Sortino, Sharpe...) can be found in the financial_ratios.ipynb file and integrated globally in the fin_ratios.py file
Volatility modeling is performed in the volatility.ipynb file
Prediction with prophet is performed in the Multivariate Time Series Forecast.ipynb file

Filtering actions for the portfolio is partially done with the shortlist.ipynb file and its results are stored in the industry_cluster_comparison.xlsx file

Filtering and selecting relevant data is performed in the feature selection.ipynb file and the results are stored in the feature_selection.xlsx file.
