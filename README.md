# mp1_sharesnalyzer
#PROJECT SUMMARY

Mini project as part of 3 months bootcamp at Institute of Data (Singapore). 

Objective: 
1. Identify top sectors contributing to S&P500 performance
2. Determine the growth of top sectors over 5 years and the rate of return
3. Investigate Big Tech stocks performance over time

#STEPS TO REPRODUCE CODE

1. Refer README.txt for libraries needed
2. Code files and Dataset.csv as below:

code files

1. Data preparation/pulling (including web scraping) on SP500 index : s&p500_prepdata.ipynb
2. Data query_organize on SP500 index : s&p500_sql.ipynb
3. Exploratory data analysis and visualisation on SP500 index : sp500_eda.ipynb
4. Exploratory data analysis and visualisation on Big Tech stocks : bigtech_eda(stock_return).ipynb

Dataset.csv

Raw dataset: 
sp500_stocksprice2019_23.csv
sp500_name_info.csv

Semi-processed dataset (share price full by sector):
sp500_consumerdprice.csv
sp500_financialprice.csv
sp500_healthcprice.csv
sp500_industrialprice.csv
sp500_ITprice.csv

Processed data (mean of daily returns according to industry): 
msp500_consumerd.csv
msp500_financials.csv
msp500_healthc.csv
msp500_industrial.csv
msp500_infotech.csv

Cleaned dataset to reproduce charts: 
sp500_sectorcount.csv
sp500_sectormean.csv
bigtech_stock.csv
