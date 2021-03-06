# stock-analysis

# VBA Challenge

## The purpose of this project are as follows: 

- to refactor Module 2 (stock analysis) solution code to loop through all the data one time to collect the same information. 
- to determine whether refactoring the code successfully made the VBA script run faster.
- Finally, to present a written analysis that explains the findings.

## Results: 

### Stock performance between 2017 and 2018.
Results from the analysis of the stocks dataset show that stocks performed exceptionally well in 2017: average return: 67.32%, median return: 42%, compared to the disappointing performance of 2018 with average return of -8.51% and median return: -12%. 
The stocks that led this high performance in 2017 are DQ, SEDG and ENPH, all returning 199.4%, 185%, and 130%, respectively. Further, while overall stocks performance in 2017 was positive, one stock (TERP) stands out as having a negative return of -7.2%.
The stocks that led the overall negative and disappointing performance of 2018 are DQ, JKS and SPWR, all returning -62.6%, -60.5%, and -44.6%, respectively. While overall stock performance in 2018 was negative, two stocks  RUN and ENPH returned exceptionally positive returns, 84% and 81.9%, respectively.
(See images of results in the “Resources” folder titled “Stocks_Performance_2017” and “Stocks_Performance_2018”.)

### Execution times of the original script and the refactored script.
The original script and the refactored script both provide the same result (as stated above), however the refactored script run the code in a much faster time for both years, 2017 and 2018, than the original script.
(See images of execution times in the “Resources” folder titled “OriginalScript_Runtime_Result_2017” and “OriginalScript_Runtime_Result_2018”.)

## Summary: addressing the following:

### Advantages of refactoring code
- Refactoring can make the code/program easier to understand.
- Refactoring can make the code more organized.
- Refactoring can be used to reduce the length of the code, hence making it easier to maintain.
- Can help to execute the code/program faster.

### Disadvantages of refactoring code
- Conducting a refactoring exercise can be time consuming.
- If not executed properly, refactoring can introduce new bug into the code.

## How these pros and cons apply to refactoring the original VBA script?
- Refactoring the VBA script helped to reduce the amount of time required to run the script for both years, 2017 and 2018. While it took 0.4460988 seconds and 0.484375 seconds to run the original script for 2017 and 2018, respectively, it took 0.1523438 seconds and 0.1171875 seconds to run the refactored script for the two years, respectively. See image in “Resources” folder title “OriginalScript_RunTime_Result_2017” and “OriginalScript_RunTime_Result_2017”.
- Refactoring the VBA script reduced the length of the script. While the original script has 71 lines of code, the refactored script has only 59 lines of code. This makes the refactored script more manageable and easier to understand than the original script.
- Conversely, making changes in the refactored script to reduce code length and to make it easier to manage took additional time to execute. This can affect a project that is highly time-sensitive in a negative way.
- Also, while trying to complete instructions for refactoring the VBA script I made some mistakes that require debugging, and which resulted in spending more time to execute. 

