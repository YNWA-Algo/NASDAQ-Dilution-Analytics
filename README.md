# NASDAQ-Dilution-Analytics
****Business Problem****:

This work is aimed at analyzing the impact of dilution – both directional and magnitude on stocks that trade on the NASDAQ. The outcome of this analysis may inform when to go long, avoid or short certain stocks based on S1 or S3 filings and other factors.

****Results:**** ***This portion is to be updated as this project is still WIP****
[This is a place holder - Decision recommendation - Operating cost per client is driven by other factors other than the NAV. While the NAV amount or portfolio value has some impact on servicing cost, it has the least impact compared to 
1.	Number of cashless securities in the portfolio
2.	Proportion (%) of non-listed securities.
These two factors above have an outsized impact on the daily operational effort needed to service a portfolio, complete pricing, reconciliation, back and middle office activities to validate the end of day/week/month NAV. Regression equation generated to show factors relationship to response (Y) = effort and serve as foundation for new pricing model. Place Holder]

****Tech Stack and other Resources:****
1.	Google Co Lab
2.	Proprietary Data Collection Plan and Collection template
3.	Google Finance.com
4.           Dilution tracker.com
5.           GitHub

****Approach:****
The first step per the data collection plan is to fetch all active NASDAQ tickers from google finance. This list is saved in a CSV file. This file/list will be used to filter or fetch data from other websites either to support this project or other related projects. The list is stored in the CSV file name: Nasdaq_tickers.CSV. The python code to fetch the tickers symbols -> NASDAQtickers1_Google.ipynb
