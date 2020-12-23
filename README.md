# Stocks for Steve

## A Bit of Background
Steve’s parents have come to him for help in the stock market, and he know just who to turn to. This Excel workbook was built to sort through a large amount of stock market data and provide easily to interpret results to the end user (Steve’s parents). 

## The Results
Originally, the script performed about ½ a second slower. It has since been optimized in order to work well with larger data sets. The refactor consists of using arrays of data as opposed to individually searching for each stock ticker

### But What Times Were Ran?
The script ran the 2017 data in about 1.29 seconds while running the 2018 data in about 1.30 seconds. The message box for the times are shown below.

![](https://github.com/thomasstvr/stock-analysis/blob/main/VBA_Challenge_2017.png)

![](https://github.com/thomasstvr/stock-analysis/blob/main/VBA_Challenge_2018.png)

### A Slight Discrepancy 
As you may notice, the data shown for Daily Total Volume of the AY ticker is not that of what has been shown on the challenge directions. Our data shows 128,747,900 in 2017 while the directions show 136,070,900. A similar discrepancy exists with the 2018 results. This is because several rows of the data are not label with an AY ticker, they are simply left blank. It would be improper to modify the original data, therefore the results and data were left as is.

## Summary
With refactoring, our script ran faster than the original we had wrote and therefore would be much more advantageous in use on much larger data sets. ½ a second may not be much when using the given data set but this small amount of time can be largely multiplied as the data set increases in scope. If a certain script is going to used often, especially with very large data sets, refactoring is crucial in saving time and computing power. 
