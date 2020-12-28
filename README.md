# YTD Multi Stock Data Analysis 
## Overview of Projec
This project provides stock market analysis over last few yeas across multiple stocks. The effort will also focus on accuracy, efficiencies, data formatting and customer experience.  

### Purpose & Scope of this Effort
* Year Parameter - Input control allowing the user the ablity to enter the year of analysis on the dataset to be processed.
* Title - Dynamic title with the year parameter be the variable value
* Column Headers - Column headers to support data visualization
* Dynamic grid - data population and YTD return calculation
* Formatting - Font, style and conditional formatting to provide visualization on negative and positive returns
* Performance - Ensuring the code can handle large datasets and meet customer experience.

# Results
### Performance Analysis based on programming logic implemented
* The below table of data provides multiple ways to acheive the end result. As much as we need to provide data accuracy, performance is also equally important. For diffrence in code logic, refer to the subroutine in the macro file. The table below lists each subroutine name. Every subroutine returns the same result set. the only diffrence is the runtime. Screen shots for each of the analysis is saved to resources folder and the file name should match the subroutine name.

![RunTime Comparison Report](/Resources/RuntimeComparisonTable.png)
<img src=/Resources/RuntimeComparisonTable.png
     alt="Runtime Analysis Report"
     style="float: left; margin-right: 10px;" />

### Challenges and Difficulties Encountered
* As a programmer, we look for  What, When, Why, Where and Who as part of the requirements. This exercise was very challenging as the HOW was defined. Especially it took  several debugging activities to determine the logical error in step 3d. As I was using a "nested if" to write the logic and following the directions in step 3d was resulting in a wrong index and wrong output. Since the pseudo-code was not very clear and step 2a & 2b asked to use "nested For Loop" was misguiding the logical flow.   

## Summary
  - Our returns are based on closing prices on the first and last market days of the year. Based on this data we may show postive or negative returns for a full year, however we would not know weekly/bi-weekly, monthly or quaterly trends. Just by looking at EOY returns will allow for portfolio changes yearly whereby missing out on some potential profits/limiting losses during shorter frequencies.
  - Having availability of hourly trends will also help in some profit taking during the day or potentailly readjusting portfolios
  
