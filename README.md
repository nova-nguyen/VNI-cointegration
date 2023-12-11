# Vietnam Stock Index Cointegration Analysis
*by Nova Nguyen - novanguyen1811@gmail.com*
## Project Description
This project aims to examine changes in the level of long run cointegration as well as short term linkages that the Vietnam Stock Index displays with other key trade partner countries over time, especially during financial crises such as the 2008 Global Financial Crisis and Covid-19 lockdown and supply chain crisis. Other indices include: US, China, Hong Kong, Japan, South Korea, Singapore, Thailand, Malaysia, Indonesia, the Philippines.
## Codes and Resources
* Coding language: R version 4.3.1
* Packages: xts, dplyr, astsa, tidyr, tseries, lmtest, fBasics, leaps, urca, lubridate, aTSA, vars, tsDyn
## Data Sources
Data is collected from Investing.com, Yahoo Finance, Walls Street's Journal databases open source for non-profit and non-liable purposes as outlined on the websites' Terms and Conditions. For each index, the dataset includes: Date, (Closing) Price, Open, High, Low, Volume, Change(%). Closing price will be used to represent daily datapoint. The aggregated dataset to be used for analysis merged by common trading date to be used for analysis will have each data cell containing continuous variable information of price points of respective countries on the corresponding date. The sample ranges from 1 Oct 2003 to 1 Oct 2023.
