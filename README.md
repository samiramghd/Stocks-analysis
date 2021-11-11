####Stocks-Analysis
###Overview of Project: Explain the purpose of this analysis
In this project we are trying to expand the dataset to include the entire stock market over the last few years. Although  green_stocks works well for a dozen stocks, it might not work as well for thousands of stocks and even if it does, it may take a long time to execute.
In this VBA_challenge we are going to edit or refactor green_stocks to loop through all the data one time in order to collect the same information as green_stocks Then, we determine VBA_challenge made the VBA script run faster.


###Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script

we are going to make some changes on green_stocks code and make it easier to understand, faster, more efficient and use less memory. in VBA_challenge we are using a for loop and in that loop we collect all th information we need and store it in an array, so we have three array (tickerVolumes, tickerStrtingPrice, tickerEndingPrice) which keep the results and tickerIndex to access the correct index across the four different arrays.
![This is an image](ticker.png)

![This is an image](firstloop.png)

 then with another for loop we print all the arrays content as an output. which makes it faster and easier instead of going through all the data every time and printing output and doing it again and again.
![This is an image](output.png)

now that we are almost familiar with the code we want to compare the results to see the efficiency.
the first time we run VBA-challenge code for 2017

![This is an image](VBA_challenge_2017.png)

and now the second time 

![This is an image](VBA_challenge2_2017.png)

when we compare these two pictures we realize the first time we run the macro, the elapsed time is longer than second time because computer resources need to be allocated to run the macro, Once allocated, these resources are ready for subsequent runs. and the same thing is happenning with 2018
the first time we run VBA-challenge code for 2018
![This is an image](VBA_challenge_2018.png)

and now the second time
![This is an image](VBA_challenge2_2018.png)

and in these pictures we can see which stock is been better and which year is been a better year for stocks. in 2018 almost all stocks had been improving and all are green except TERP which dropped 8% and in the results we can see which one had the most improvement and 2018 is been a better year for stocks in compare of 2017.

and at the end we're comparing green_stocks and VBA_green run time.
here we can see run time for green_stocks 2017 and 2018

![This is an image](green_2017.png)

![This is an image](green_2018.png)

when we compare run time elapased between green_stocks and VBA_challenge we can see how more efficient and faster is VBA_challenge refactored code.


### Summary: In a summary statement, address the following questions

1. What are the advantages or disadvantages of refactoring code?

 After refactoring, the code is fresher, easier to understand or read, less complex and easier to maintain. Disadvantages of Code Refactoring, Time Consuming, You may have no idea how much time it may take to complete the process. It may also land you into a situation where you have no idea where to go.
 Although refactoring does not add features or functionalities in a software system, it is sharp weapon for developers in their maintenance activities. 
 Advantages:
 - Refactoring is a really good weapon to maintain the code
 - easier to understand
 - Make the code clean and organized
 - Help to follow principles and less complexity
 Disadvantages:
 - hard and risky when the application is big
 - when the existing code doesn't have proper test cases it's hard to maintain it
 - risky when developers do not understand what's all about

2. How do these pros and cons apply to refactoring the original VBA script?
 Refactoring the code is not always easy. the code has to be easy to read, if we want to come back to code after a while to do some more changes and troublshooting, it shouldn't be hard to understand otherwise we haven't done a good job on refactoring the code.
