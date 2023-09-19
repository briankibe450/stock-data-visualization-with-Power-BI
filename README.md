# Stock Portfolio
This project is to create a performance dashboard of the list of stocks that are carefully randomly selected. The date which the investment started is March 5th, 2021. The comparison with the current performance is based on the closing price of the date.

### 1. List of Stock
Power BI imports core data from Yahoo Finance website via a Web portal. The links are listed below.
- VNQ : [https://ca.finance.yahoo.com/quote/VNQ/history?p=VNQ&.tsrc=fin-srch](https://ca.finance.yahoo.com/quote/VNQ/history?p=VNQ&.tsrc=fin-srch)
- RBNK.TO : [https://ca.finance.yahoo.com/quote/RBNK.TO/history?p=RBNK.TO&.tsrc=fin-srch](https://ca.finance.yahoo.com/quote/RBNK.TO/history?p=RBNK.TO&.tsrc=fin-srch)
- SMH : [https://ca.finance.yahoo.com/quote/SMH/history?p=SMH&.tsrc=fin-srch](https://ca.finance.yahoo.com/quote/SMH/history?p=SMH&.tsrc=fin-srch)
- SOXX : [https://ca.finance.yahoo.com/quote/SOXX/history?p=SOXX&.tsrc=fin-srch](https://ca.finance.yahoo.com/quote/SOXX/history?p=SOXX&.tsrc=fin-srch)
- AAPL : [https://ca.finance.yahoo.com/quote/AAPL/history?p=AAPL](https://ca.finance.yahoo.com/quote/AAPL/history?p=AAPL)
- RY.TO : [https://ca.finance.yahoo.com/quote/RY.TO/history?p=RY.TO&.tsrc=fin-srch](https://ca.finance.yahoo.com/quote/RY.TO/history?p=RY.TO&.tsrc=fin-srch)
- KBWD : [https://ca.finance.yahoo.com/quote/KBWD/history?p=KBWD&.tsrc=fin-srch](https://ca.finance.yahoo.com/quote/KBWD/history?p=KBWD&.tsrc=fin-srch)

### 2. Spreadsheets
Total of four spreadsheets is imported into the BI project. They create a simple database that intertwines with each other. 
- daily trend: summary of the daily closing price between March 5th to 25th of total stocks on hold. Also, it calculates the daily loss or gain compared with the initial cost.
- holdings: summary of the holdings and the price. Also, the data frame consists of total value and the gain or loss on individual holdings.
- stock: daily open, high, low, close, adj close, and trade volume of each holding for the past year.
- type: categorical summary of each holding. Also, contains a target price for each holding.

### 3. DBRM Diagram
![DBRM](https://raw.githubusercontent.com/danypark91/StockPortfolio/main/DBRM.PNG)
