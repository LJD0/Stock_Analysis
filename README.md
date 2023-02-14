# Stock-Analysis


## Overview of Stock Analysis
    The purpose of this study was to see the yearly returns for a dozen stocks that are on the clients watch list. With that information determine the stocks from that list that may have good returns for the future.

## Results
    Ultimately only two stocks performed positively across both years of study; tickers "ENPH", and "RUN". While looking at the year 2017 we can see that most of the stocks on our watch list had positive yearly returns, and the opposite became true in 2018. It would suggest that there were outside factors that led to the decline of the whole market to decline that year or the market had a run up in 2017 and possibly years previous leading to a cool off period in 2018. It would seem that any of the stocks on are list have the potential to rise, based on their sharp decline over the year of 2018, but because there were only two that had performed positively even while the market was on a downtrend, our best results may be found by investing in either "ENPH" or "RUN".


### Summary
    Our initial code for AllStockAnalysis was able to perform all of the essential functions we needed to complete our analysis. The drawbacks are we wrote this code in a language that programmers can understand, i.e. using variable like "i" and "j" to iterate through our stock tickers. With our refactored code it is plain to see the purpose of each variable and how it is being referenced. The other drawback to the original code was the variable were not stored independently of each other inside of a list. With the refactored code each ticker has a specific value of Volume and a Start and End Price each specific to the ticker. Our original code wrote over each of those variables as needed for each ticker. 
    The major difference in our refactored code is the arrays we used to store our individual totals for each ticker. The advantage to storing the data that way is that we can now access any given variable for any given ticker at any time. With the original code the Volume and Start/End Prices were overwritten each iteration fo the loops we used. If we were to try and call back to the volume variable the system would only give us the most recent iteration, not the one we may need.
