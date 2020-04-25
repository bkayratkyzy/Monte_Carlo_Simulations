# p1-Formula_1 
                           
**Proposal**

**Title:**  Stock sector analysis using Monte Carlo , statistical functions and portfolio optimization. 

**Team Members:**

1. Kelly Michelle Maldonado
2. Bulbul Yestemissova
3. Gabriel Klurfan
4. Chris Costanzo

**Project Description:**

Stock sector analysis using monte carlo and statistical functions.

Formula 1 is proposing to build an efficient and accurate financial model to analyze the state of the economy using sector analyses to compare how each sector performs relative to different market conditions. Some measures of the state of the economy include GDP, retail sales, unemployment, consumer confidence, etc. 

We will be analyzing the different sectors of the S&P 500 and forecasting with Monte Carlo. We will also look at S&P Value and Growth indices using Monte Carlo. These indices define growth and value using S&P's definition of growth (using sales growth, earnings change to price, and momentum) and value (using book value, earnings, and sales to price). 

Monte Carlo allows us to put confidence intervals on each sector. We will also use ratio analysis (p/e, p/sales, p/book), linear regression and time series analysis. Sector specific metrics such as standard deviation, variance and covariance, and performance versus the S&P 500 will also be used. 

We are using the S&P 500 index because it is a universally accepted, well documented index with readily available sector breakdowns. It allows us to do a top down analysis on a sector level with the option of drilling down to stock level if desired. We expect our analysis could easily be expanded to broader indexes such as the Russell 3000. 

We will construct a preferred portfolio using the different sectors by optimizing weights using the PyPlotOpt library. We will test this portfolio using backtesting (PyAlgoTrade).

APIs and JSON data will be used to obtain data. CSVs and a SQL database will be used as needed. 

Finally,  we will survey the pandemic behavior of the sectors and indices in an attempt to identify which sectors/companies could compose an "Emergency-Ready" portfolio, one that benefits from current pandemic conditions (e.g., Technology, Health Care) 



**Research Questions:**

What is the current state of the economy and how does this compare to pre-pandemic? 

Pre vs post pandemic comparisons:  Are some sectors outperforming or underperforming during the pandemic?

Which sectors will experience growth as a result of the outbreak?

What sectors of the S&P 500 appear most attractive for investment?

What investment style appears more attractive (Growth or Value) for investment?

Are Growth stocks or Value stocks underperforming/outperforming? Pre and post pandemic?

Is there a preferred mix of sectors/investing style post pandemic? What if pandemic trends continue for another year? What if the pandemic ends quickly?

**Datasets to be used:**

GoogleFinance/Alpaca/Quandl - S&P 500 sector etfs, S&P 500 growth and value indices, Russell 3000. Valuation ratios - Price to Sales, P/Es, Price to book. 


**Rough breakdown of tasks:**

Kelly Michelle Maldanado

    API Alpaca
    Data Clean up
    Consumer Discretionary Monte Carlo
    Consumer Staples Monte Carlo
    S&P Growth Monte Carlo
    
Bulbul Yestemissova
    
    API Alpaca
    Data clean up
    Energy Monte Carlo
    Financials Monte Carlo
    S&P Value Monte Carlo

Gabriel Kurflan

    GoogleFinance
    Data Clean up
    Health Care Monte Carlo
    Industrials Monte Carlo
    Utilities Monte Carlo
    

Chris Costanzo

    API Quandl
    Data cleanup
    Materials Monte Carlo
    Real Estate Monte Carlo
    Technology Monte Carlo
    

**Sectors of the S&P 500

CONSUMER DISCRETIONARY

CONSUMER STAPLES

ENERGY

FINANCIALS

HEALTH CARE

INDUSTRIALS

MATERIALS

REAL ESTATE SECTORs

TECHNOLOGY

UTILITIES

**S&P Growth and Value indexes:

S&P Growth Index (Ticker = SGX),
S&P Value Index (Ticker = SVX)










