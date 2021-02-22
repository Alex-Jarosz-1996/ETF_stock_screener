# ETF_stock_screener
This script collects different ETF's from the Morningstar website.
The purpose of this script is:
- to collate ETF data off the Morningstar website
- determine which ETF's are the best performing based on
    (a) 6 month return
    (b) YTD return
    (c) 1 year return
    (d) 3 year return

There are 4 different code chunks to run the code:
(1) ### (A) - Loading in the required packages                              -> etf.py
(2) ### (B) - Saving the Morningstar web-page as an excel file with Pandas  -> etf.py
(3) ### (C) - Separating the Morningstar df into different df's             -> etf.Rmd
(4) ### (D) - Printing recommendation                                       -> etf.py
Run them sequentially (i.e. from (1) - (4))

Code functionality:
When prompted the code will ask for your input for:
 - Top performing ETF's over the last 6 month period
 - Top performing ETF's over the last 1 year period
 - Top performing ETF's over the last 3 year period
 - Top performing ETF's over the YTD period
 - Top performing ETF's for YTD and 6 month
 - Top performing ETF's for YTD, 6 month and 1 year
 - Top performing ETF's for YTD, 6 month, 1 year and 3 years

 Future iterations:
 - Potentially incorporate information from https://etfdb.com/etfs/ (this is TBD however)

 Recommendation:
 - Recommend to run the script on a code-chunk by code-chunk basis
