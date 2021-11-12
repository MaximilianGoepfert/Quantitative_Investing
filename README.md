# Quantitative Investing
This repository contains my projects centered around quantitative investing.

### Disclaimer 
The content presented in the following is entirely informative. None of the content presented constitutes a recommendation that any particular security, portfolio of securities, transaction or investment strategy is suitable for any specific person. Futures, stocks and options trading involves substantial risk of loss and is not suitable for every investor. The valuation of futures, stocks and options may fluctuate, and, as a result, clients may lose more than their original investment. \
_All trading strategies are used at your own risk._

## Quantitative Momentum Strategy
- Built an investment strategy that selects the stocks with the highest price momentum
- Also made use of a number of value investing criteria
- Created an equal-weight portfolio of twenty stocks
- Considered stocks listed on the S&P 500 Index

### Code and Resources Used
__Python Version__: 3.7.4 \
__Libraries__: numpy, pandas, pyEX, requests, scipy, forex_python, math, pickle, xlsxwriter, os \
__IEX Cloud API__: https://iexcloud.io/core-data/ \
__Inspiration & General Structure__: https://github.com/nickmccullum/algorithmic-trading-python \
__Piotroski Score__: https://github.com/AshJAnderson/YouTube-Finance \
__Momentum Strategy__: https://taldavidson.com/quantitative-momentum/quantitative-momentum-strategy/ \
__Idiosyncratic Momentum__: https://alphaarchitect.com/2017/05/02/swedroe-spotlight-enhancing-momentum-strategies-via-idiosyncratic-momentum/ 

## Financial Dashboard
- Built a Tableau dashboard presenting a selection of stocks selected through our Quantitative Momentum Strategy
- Dashboard mainly tracks the intraday movement of twenty stocks on a particular date
- Also gives an overview over a couple of other statistics such as industry sector or market cap
- Embedded the Momentum Strategy workbook from within GitHub

### Resources Used
__Tableau Version__: 2020.4.10 \
__Dasboard Logo__: <sub> https://cdn.dribbble.com/users/196252/screenshots/3120663/_98e577de78282073be3632fad0966ad60326d10c95a2223bc5_pimgpsh_fullsize_distr.jpg </sub>

This is what a page of the dashboard looks like: <br/> <br/>

![Screenshot](https://github.com/MaximilianGoepfert/Quantitative_Investing/blob/main/FD_Screenshot.png)

<br/> <br/>
The full dashboard may be found at: https://public.tableau.com/app/profile/maximilian8268/viz/FinancialDashboard1_0/FBFrontpage
(Link currently inactive)
