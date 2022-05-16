# VBA Stock Analysis

## Overview of Project

Steve is now looking to do a little more analysis on the entire stock market over the last few years. He wants to expand the data set and perform the same analysis report for more than the 12 stocks we initially evaluated. 


### Purpose

The purple of this challenge is to *Refactor the data set by fixing the initial code to make the process much faster to process. Instead of running through each of the columns and rows separately, we'll be introducing a function known as *Index in order to run through the entire array of data at once. We're looking to simplify the process for Steve so he is able to move through the data set quicker.


## Results

As per the Code results shown in the image below, we modify a few steps from the original code. First, we initialize the tickerIndex by setting it to zero and then creating three output arrays to run through the dat set together. What's also different here is tickerVolumes is set to *Long and both starting and ending prices are set as *Single due to it requiring less bytes. A loop is then created setting all arrays o zero before we loop through all rows. Then we follow the same process bu use *tickerIndex in the code to check the if the current row is the last or first row, and to increase volume for the current ticker all at once as we run through each row.

![VBA_Code](VBA_Challenge_Code.png)


Below are the run times on each of the analysis reports run for both 2017 and 2018.



## Summary

    1) Advantages/Disadvantages

    2)Pros/cons apply to refactoring original VBA script
