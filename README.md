# An Analysis of Module 2 Challenge Project-VBA Script Refactoring
Performing analysis on the editing & refactoring process on the Module 2 code to determine whether it can run more efficiently.  

## Overview of the Project

Refactor the Module 2 solution code & measure performance.  Determine if improvements were made and present and explain the findings.  
### Purpose and Background 
The purpose of our work was to use the original All Stocks Analysis VBA code and improve the performance or this tool.  
We can analyze much larger sets of data more efficiently such as the entire stock market over the past few years.    

## Results 

Timed results before the refactoring.  Please note: these files can be found in the Resources folder.   

![Original 2017 run time with results old code](https://github.com/mjrotter4445/stock-analysis/blob/main/Resources/2017%20run%20time%20with%20results%20old%20code.png)

![Original 2018 run time with results old code](https://github.com/mjrotter4445/stock-analysis/blob/main/Resources/2018%20run%20time%20with%20results%20old%20code.png)

The end result was to look like this.   
![Chart_ExamplesProvided](https://github.com/mjrotter4445/stock-analysis/blob/main/Resources/Examples%20Provided.png)  

 Below we verify that our newly reconstruted script has indeed accomplished the following goals:
 First, it matches the example data/result given in the assignment and Second, it improves the speed of running the program. The refactored programs/macros ran significantly     
 faster.  The processing times were approximately .4 seconds instead of .6 seconds.    
  
  
 ![2017 run time refactored code](https://github.com/mjrotter4445/stock-analysis/blob/main/Resources/2017%20run%20time%20refactored%20code.png)  
 
 ![2018 run time refactored code](https://github.com/mjrotter4445/stock-analysis/blob/main/Resources/2018%20run%20time%20refactored%20code.png)  
 
 ## Summary 
The advantages of refactoring code in general are 1) the ability to analyze larger data sets with speed and to better organize, clean, and maintain code.   
The disadvantages of refactored code is that refactoring may run into underlying architecture issues and problems.   It takes a lot of skill and time (expense) 
to refactor code, especially code written by other programmers.    
In this exercise, the refactored code is intended to improve the performance of this DQ Analysis program and it did.   
After code was refactored, I ran the stock analysis, to confirm that our stock analysis outputs for 2017 and 2018.  
The refactored programs/macros ran significantly faster.  The processing times were approximately .4 seconds vs. .6 seconds. 
The improvment speed is approximately 30%.  The refactored programs ran 30% faster.    
