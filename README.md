# Bank of Canada Monetary and Markets Statistics

* This notebook provides examples of some of the monetary policy and financial market statistics provided by the Bank of Canada. It pulls the data into dataframes that can be used for further data transformation and analysis.

* The notebook uses the data available as CSV files from the Bank of Canada website and can be further enhanced by integrating with the Bank of Canada APIs (https://www.bankofcanada.ca/valet/docs#valet_api) and other data providers such as Bloomberg Professional Services.

* The notebook is using the following CSV files from the BoC website:

    1) Canadian Overnight Repo Rate Average (CORRA): CORRA.csv - updated every day at 9:00 am at https://www.bankofcanada.ca/rates/interest-rates/corra/

    2) Securities Repo Operations: Sec_Repo.csv - updated every day at 10:15 am at https://www.bankofcanada.ca/markets/market-operations-liquidity-provision/market-operations-programs-and-facilities/securities-repo-operations/

    3) Money Market Yields: money_market.csv - updated daily at https://www.bankofcanada.ca/rates/interest-rates/money-market-yields/

    4) Selected Bond Yields: bond_yields_all.csv - updated daily at https://www.bankofcanada.ca/rates/interest-rates/canadian-bonds/

    5) Daily Exchange Rates: FX_RATES_DAILY-sd-2017-01-03.csv - updated daily at https://www.bankofcanada.ca/rates/exchange/daily-exchange-rates/

* For this notebook to work, the above files must be downloaded and saved as CSV (Comma delimited) (*.csv) files in the same folder as this notebook.

* To download/refresh the data, click on each of the above links, locate ***"Data available as: CSV, JSON and XML"***, right click on ***"CSV"*** and save the file without changing its name in the same location as this notebook..