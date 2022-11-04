# An Analysis of Stock Performace for Environmental Companies in 2017 to 2018

## Overview of Project

In this analysis, we look at stock data from 2017 and 2018. The focus of the analysis is the trading volume and return of a selection of 12 stocks of environmentally focused companies. We also consider the code performance of different implementations of the analysis with an eye towards anaylzing the entire stock market.

## Analysis of Stock Performance from 2017 to 2018

Our analysis gives a stark contrast between the performance of the companies of interest in 2017 and 2018

[[[[links for 2017 and 2018]]]]

Broadly speaking, we see that returns in 2018 are down across the board, even as trading volumes are up for all but two of the stocks. The only exceptions to this are ENPH and RUN. This gives an initial suggestion that these two companies are robust investments even when there is a broader downturn in the enviromental sector, so any enviromentally focused portfolio should include these two companies as major investments. This is, of course, only a trend across two years, so we recommend further investigation to see if these trends hold strong over time. 

## Results

In our coding of the analysis we refactored our initial algorithm to only pass through the stock data one time. Below are the runtimes of each version, with the refactored runtimes second.

- 2017 : [[[[[Links for 2017 runtimes]]]]]

- 2018 : [[[[[Links for 2018 runtimes]]]]]

As we can see, the refactored runtimes are roughly 500 to 1000 times faster. This does require a bit more working memory, as we store all of our data for the analysis in a number of arrays to avoid unnecessary looping. This could potentially cause crashing issues with extremely large data sets, but for the volume of stocks on a standard exchange, this should run fine even on a computer with older specifications. As such, moving towards a full market analysis, we recommend the refactored algorithm.
