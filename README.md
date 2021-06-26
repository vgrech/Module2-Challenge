# Module2-Challenge
Excel - VBA

# Overview of Project: Explain the purpose of this analysis
The purpose of this analysis is to refractor the Module2 solution code and create a more efficient method for analyzing large datasets, stocks specifically. After refractoring the code to achieve the same end goals we need to determine whether or not the refactored code was more efficient aka did the code run quicker after. 

## Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.
When looking at the side by side comparison (see image below) of the refractored code results of stock data from 2017 and 2018 one can see that overall 2017 outperformed 2018 in returns. When taking a deeper dive into the data, we see that although almost every stock's return went down RUN's increased dramatically and ENPH remained above 80% whereas the rest experienced losses instead. Another insight we can draw from the data comparison is that although TERP experienced loss in both years, it's amount of loss decreased in 2018 while maintaining a lower total daily volume than most other stocks.  
![](VBA_Challenge_2017.PNG)
![](VBA_Challenge_2018.PNG)

I ran into glitches after creating the loop in the original script and noticing something was incorrect in the code as the returns were all appearing to be "0.0%" that whenever I attempted to edit the code my VBA and excel windows would stop responding and I would need to restart the program. This happened every time (over separate days of attempts) so I was not able to fix the original script. This undoubtly had an affect on the execution times. However, I belive that given that the 2017 data appeared to run faster with the refactored code than the original it would have been the case for both if the orginal script had been able to have been edited correctly. I also noticed that 2018 had longer execution times which I believe could be due to the negative caluclations taking more time to execute over positive ones since there were many more loses in 2018 than 2017. 

# What are the advantages or disadvantages of refactoring code?
There a

# How do these pros and cons apply to refactoring the original VBA script?
