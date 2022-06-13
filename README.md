# ****Stocks-Analysis****
## Overview of Project
- To see how different green energy stocks fared in relation to that year in the stock market by using the green stocks dataset, and VBA to find the stock's total daily volume and annual return.
### Purpose
- Analyze the Green stocks data to determine which green stocks should be invested in using VBA to shorten the analysis time. 
- Determine if Refractoring or editing the Stock Market Dataset with VBA solution code will make it more efficient or faster. 
## Results
- Examples of code:
-  
- Compare the stock performance between 2017 and 2018
- ![stock_Outcome](https://user-images.githubusercontent.com/106709942/173264167-6be6ddeb-d907-4b64-8093-6a8be2fcf37d.PNG) 
  - As seen above, All green stocks in 2017 were able to be in the green, and provide a return with the exception of TERP stock being in negative (-7.2%)
  - 2017 green stock return leader were the following: DQ, SEDG, and ENPH. 
  - All green stocks in 2018 are in the red with negative returns with the following exceptions: ENPH (+81.9%), and RUN (+84%). 
- Execution times of the original script and the refactored script.
  - Execution times using the original code

     ![This is an image](https://github.com/albalushiaj/stocks-analysis/blob/main/Resources/VBA_AllStock_2017.PNG)
    
     ![This is an image](https://github.com/albalushiaj/stocks-analysis/blob/main/Resources/VBA_AllStock_2018.PNG)
  - Execution times using the refractured code 
  
     ![This is an image](https://github.com/albalushiaj/stocks-analysis/blob/main/Resources/VBA_Challenge_2017.PNG)
     
     ![This is an image](https://github.com/albalushiaj/stocks-analysis/blob/main/Resources/VBA_Challenge_2018.PNG)
          
  - Based on the execution times, the refactored code runs 0.0468755 faster for 2017, and for 2018, 0.0234375 seconds faster than the original code making it more efficient.
## Summary
-  The advantages of refractoring is clean code with shorter, self-contained methods and classes is characterized by better testability. Improved legibility improves the comprehensibility of the code for other programmers while on the other hand, the disadvantages are imprecise refactoring could introduce new bugs and errors into the code, An improved code is often difficult for the customer to recognize its value, since the functionality stays the same(the benefit is not self-evident).
-  In general, when it comes to programming, follow the advice of the acronym DRY: Don't Repeat Yourself. If you're reusing a piece of code over and over again, there's probably a better way to do it like refractoring. Consider refactoring as a cleaning up process where it is simplifying a process, and making it more efficient while maintaining a neat code system. 
-  *“Less stuff means less to clean, less to organised, less to store, less mess”* *"Plan your work, and work your plan."- Napoleon Hill*
  -  By following these two quotes, it will be easy to understand code if a clutter was taken out, a plan was made, and you follow the plan. By doing that, you can reap the benefits of refractoring in VBA. 

