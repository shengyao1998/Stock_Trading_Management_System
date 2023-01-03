# PROGRAM FEATURES Template Version
PROGRAM FEATURES Template Ver.    : Ver. 1.2 <br>
Last Modified Date                : 3 Jam 2023 <br>


## Functional Features
--------------------------------------------------------------------------------------
### FEATURES 1: User Login Page
##### Functions
Prevent unauthorised person from login into the software. 

##### Description
The program should come with a function to prevent all unauthorised person from accessing the program. Only the owner of the program are allow to access the pages. Something like a lockscreen or so.

--------------------------------------------------------------------------------------
### FEATURES 2: Personal Assest Summary
##### Functions
To show the overall financial status of the user in a Dashboard layout.

##### Description
User are opt to choose an account they wish to minitor in a Drop down list (Total 4 Options for now)
1. Overall (Sum of 3)
2. US account
3. Malaysia account
4. SG account

Then the page should showing the following items for that particular account.
Mainly showing but not limited to following Criteria:
1. Capital + Visualization Chart (Bar/Pie)
2. Tradable Cash + Visualization Chart (Bar/Pie)
3. All purchased stock market value + Visualization Chart (Bar/Pie)
4. Invested Amount + Visualization Chart (Bar/Pie)
5. Return + Visualization Chart (Bar/Pie)
6. Unrealized and Realized Profit + Visualization Chart (Bar/Pie)
7. Top 3 invested Stock
8. Top 3 Watch List Stock


--------------------------------------------------------------------------------------
### FEATURES 3: Stock Trading Logbook
##### Functions
To record down all the Stock traded, allow the user to trace back the record up to 10 years. Any data beyond 10 years will be removed automatically.

##### Description
This will be the general layout of the logging system:

|        GENRAAL INFO          |      BUY       |      SELL        |      NET        |
--------------------------------------------------------------------------------------

For the GENRAAL INFO section, following aspect will be included:
1. Market
2. Symbol
3. Trading Status
4. Latest Devidend %

For the BUY section, following aspect will be included:
1. Buy In Date
2. Quantities
3. Market Value
4. Brokerage Fee
5. Total Cost

For the SELL section, following aspect will be included:
1. Sell Out Date
2. Quantities
3. Market Value
4. Brokerage Fee
5. Total Cost

For the NET section, following aspect will be included:
1. Total Day Held
2. Trading Profit
3. Trading Profit %
4. Devident Profit
5. Other Profit
6. Total Net Profit/Loss


Remark:
Sometime user might puchasing a stock he already own previosuly. The newly purchased unit should be compile and update into the previous entry.
Similar concept apply to Selling a stock in multiple sell transcation

--------------------------------------------------------------------------------------
### FEATURES 4: Setting Page
##### Functions
##### Description



--------------------------------------------------------------------------------------
### FEATURES 5: Cross Platform Program
##### Description
The program should be in a cross platform based, as the user will require to access that particular software from his phone (Android), PC Program (Wins11), or Web version of the software in different location during different time.


Q1. Does cross platform development means that the software had to be develop in three diff architecture, with diff programming languages, with diff env setup?

--------------------------------------------------------------------------------------
### FEATURES 6: Share Database (SQL? Server?)
##### Description
Under cross-platform environment, the entry updated through the phone version should also be reflected to the Web version, as well as PC version. All of the software should lead back to the same database.


Q1. Further research needed, does this mean that need to setup server? Setup SQL database? 





--------------------------------------------------------------------------------------
## Following features had been abandoned as it does not really suite a the Assest Managenemtn System. Instead it look much similar to Stock Trading System
### FEATURES A: Watch List
##### Functions
##### Description

### FEATURES B: Indexs
##### Functions
Show some of the important indexes real time. All the indexes should be show in Candle Chart. 
All of the indexs can be show in dashboard form

##### Description
Indexs to be include are:
1. NASDAQ
2. DOW
3. S&P 500
4. KLCI
5. CPI & PPI
6. VIX 
7. STI

Remark:
The index are not fixed. Operator are allow to add, edit, remove the indexs to better suit their current investment need.
All data can be obtain from Investing.com, or Tradingview

### FEATURES C: Bugetary Pages
##### Functions
##### Description

### FEATURES D: Stock Price Prediction
##### Functions
##### Description

### FEATURES D: Financial News Pages
##### Functions
##### Description

### FEATURES E: Stock on Hot Trading
##### Functions
##### Description
