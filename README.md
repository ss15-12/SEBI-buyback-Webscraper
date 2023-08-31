# SEBI-buyback-Webscraper
A webscraping module that extracts important buyback data from reputed stock websites 

PROCESS:
1) Choose a reputed stock website from where crucial stock data can be scraped , In my case I have used Chittorhgarh
2) Scrape the data using either Selenium or Beautiful soap module in python.
3) Consodilate all the data into a single dataframe .
4) This dataframe contains various attributes such as:
         1) Record Date
         2)Offer Opens On
         3)Last Date for receipt of Tender Forms
         4)Offer Closes On
         5)Finalisation of Buyback Acceptance
         6)Last Date for settlment of bids
         7)Last Date for Extinguishment of Shares
