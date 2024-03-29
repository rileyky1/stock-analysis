# Stock-Analysis

## Overview

### The purpose of this analysis is to compare each stock's total daily volume and percent return in 2017 to 2018 with an emphasis on refactoring the VBA code to run more effeciently. The VBA code is set up using For Loops and Conditionals to run through the two sheets of data including our 2017 and 2018 stock performance. The All Stocks Analysis sheet contains the data output after our script runs through each ticker symbol to gather total daily volume and percent return information.

## Results

### This stock portfolio as a whole performed much better in 2017 compared to 2018. All stocks excect for TERP had a positive return on investment in 2017. In 2018 only two stocks in the portfolio, ENPH and RUN, had a positive return on investment. 
![stocks2017](stocks2017.png) ![stocks2018](stocks2018.png)

### Additionally, the code is running very efficiently as evidenced by the timer snapshots included below for 2017 and 2018, respectively. 
![VBA_Challenge_2017](VBA_Challenge_2017.png) ![VBA_Challenge_2018](VBA_Challenge_2018.png)

## Summary

### Refactoring code is very helpful for managing large datasets down the road. The refactored code is meant to improve quality and make it easier for whoever is working with the data. When the code is clean and simplified, it should eliminate a number of speedbumps and questions that may take time to disect and resolve. On the other hand, refactoring code could potentially cause new, unforseen problems with functionality or a disconnect with certain variables that may not be recognized by everyone who needs to use it. What may seem like a fix to one person could be an issue for someone else.
