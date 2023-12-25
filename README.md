# Valuation
My first step to different company valuation method and strategies that I found. 
## AMD Markov Returns Excel
- Extracted 20 years worth of AMD's stock price data from Yahoo Finance. 
- Get daily returns and prove that the returns are nomal and market is efficient.
- If market is not efficient, look at the single transition probabilities and formulate simple strategy that makes more than the simple buy at open and sell at closing each day.

### Result
1. The market is not efficient and the return rate of each day is not random. We can formulate strategy based on this information. 
2. The strategy required for better return is different when you compare 20 years data vs the recent 9 years.
3. Simple buy and sell at opening and closing everyday yields average yearly return of 10% in the recent 9 years. 
4. In the recent 9 years, simple buy at open and sell at closing strategy after relatively high loss/low return day in the previous day results in average yearly return of 35%
5. Bonkers

## AMD markov chain multi transition
In the excel file, I proved that the daily returns are not random and found out the simple buy and sell at opening and closing strategy depending on the previous day's return can yield profit.
In this notebook, instead of referring to a single previous day, I will refer to 2 or more past days to choose the trading days. 

### Result
1. Referring back to 2 days to choose the days to trade leads to the best result.
2. Since this is testing of a single stock, we need to do further testing on other stocks to see if this can be applicable in general. 

## DCF
Calculate the value of AMD using discount cash flow model. 
