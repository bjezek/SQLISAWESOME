# SQLISAWESOME

# libraries used for ETF analysis
import numpy as np
import pandas as pd
import hvplot.pandas
import sqlalchemy

# Link database to sql query, tables where created?!
database_connection_string = 'sqlite:///etf.db'
engine = sqlalchemy.create_engine(database_connection_string)
engine.table_names()

# Is Paypal a good buy! 
Calculate daily returns , cumulative returns as well as hvplot demonstrations
showing returns over time from pypl. 

# Paypal Table
Created table from pypl when price was above 200 and displaying top 10
daily returns. 

# One Dataframe one ETF
right inner join code to combine dataframes from stocks into one tabel
run daily, annual & cumulativ returns. also creating hvplot to display
cumulative returns of the ETF portfolio.

# Conclusion
is far better over time to invest in ETF for lower downside risk while having the ability 
to strongly participate in upside growth over time resulting in the end total being a larger
ROI. 
# ScreenShot

![image](https://user-images.githubusercontent.com/106267420/179883548-eb60e4d6-b439-460f-9805-30934b58744a.png)
