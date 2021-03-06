# Stock Analysis using VBA
## Overview of the Project
### Purpose  
  The purpose of this analysis was to take alphabetized stock information from multiple worksheets and analyze its performance over a period of two different years.  We wrote a code that analyzed one specific stock, then refactored it to run the analysis on all of the stocks in the worksheets.  The original code was written to help a client determine if a specific stock was worth investing in, while the refactored code assisted the client in making a decision regarding all of the listed stocks.
## Results
  Refactoring the code allowed us to see the perfomance of all 12 stocks over the course of 2017 and 2018.  Pictured below are the results of both analysis.
 
 ![2017 Results](https://github.com/RyanJeffery21/stock-analysis/blob/008d21d22edd542ed2f895b25d08f6ef65077624/2017%20Results.png)
 ![2018 Results](https://github.com/RyanJeffery21/stock-analysis/blob/3564a8809fbbeb7286ec63e8607fea1f7ed7576d/2018%20Results.png)
 
 As we can see, most stocks performed well in 2017 but only ENPH and RUN had positive returns in 2018.  Refactoring our code not only allowed us to run the script for the entire database, but also reduced processing time.  The original code ran in roughly half a second, while the refactored code significantly reduced the processing time.
 
![2017 Runtime](https://github.com/RyanJeffery21/stock-analysis/blob/3e142fc7cdae7a92005b4f0312eebb29960dda6c/VBA_Challenge_2017.png)
![2018 Runtime](https://github.com/RyanJeffery21/stock-analysis/blob/079a961bab53e8e7863ad16c20ac60645aa7cd8e/VBA_Challenge_2018.png)

By adding arrays and a ticker index, we were able to loop through the data much faster and more efficiently than before.
(https://github.com/RyanJeffery21/stock-analysis/blob/b8dbe2dc2f94e386b06396fa8c2ddf456e5ffa2e/tickerIndex.txt)

## Summary
  Refactoring code is advantageous when taking a code that has been shown to work on a smaller scale and adapting to run on a larger project.  Having written the initial code gave us the advantage of knowing how it worked and how best to apply it to a broader set of data.  Difficulties could arise when working with code that we are unfamiliar with or are unable to decipher.  Both codes used in this exercise relied on the data being organized alphabetically in order to function, furthur coding could be done to organize the data in case new information is added.
