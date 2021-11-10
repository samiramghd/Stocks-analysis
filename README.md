# Stocks-analysis
this is for Stocks analysis project
####Stocks-Analysis
###Overview of Project: Explain the purpose of this analysis
In this project we are trying to expand the dataset to include the entire stock market over the last few years. Although  green_stocks works well for a dozen stocks, it might not work as well for thousands of stocks and even if it does, it may take a long time to execute.
In this VBA_challenge we are going to edit or refactor green_stocks to loop through all the data one time in order to collect the same information as green_stocks Then, we determine VBA_challenge made the VBA script run faster.


###Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script

we are going to make some changes on green_stocks code and make it easier to understand, faster, more efficient and use less memory. in VBA_challenge we are using a for loop and in that loop we collect all th information we need and store it in an array, so we have three array (tickerVolumes, tickerStrtingPrice, tickerEndingPrice) which keep the results and then with another for loop we print all the arrays content as an output. which makes it faster and easier instead of going through all the data every time and printing output and doing it again and again.
now that we are almost familiar with the code we want to compare the results to see which one is more efficient.
the first time we run green_stocks code for 2017 we get this result
![This is an image](green_2017.png)



###Summary: In a summary statement, address the following questions

What are the advantages or disadvantages of refactoring code?
How do these pros and cons apply to refactoring the original VBA script?
