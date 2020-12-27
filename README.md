# YTD Multi Stock Data Analysis 
## Overview of Projec
This project is to provide stock market analysis over last few yeas across multiple stocks. The effort will also focus on accurancy, efficience, data formating and customer experience.  

### Purpose & Scope of this Effort
* Year Parameter - Input control allowing the user the ablity to enter the year the analysis to be performed on allowing the ability to select the dataset to be processed.
* Title - Dynamic title with the year parameter be the variable value
* Column Headers - Column headders to support the data visualization
* Dynamic grid data population and YTD return calculation
* Formating - Font, style and conditional formating to provide visualization on negative and positive returns
* Perfoemance - Ensuring the code can handle large datasets and meet customer experience.

# Results
### Performance Analysis based on programming logic implemented
* The below table of data provides multiple ways to achive the end result. As much as we need to provide accuracy in data, it is equally important to user experience. performance is a key user experience aspect. For diffrence in logic, refer to the subroutine in the macro file. The table below lists each subroutine name. Every subroutone results in the same information. the only diffrence is the runtime. Screen shots for each of the analysis is saved to resources folder and the file name should match the subroutine name.
![OutcomesBasedOnLaunchDateANDCategory](/Resources/Theater_Outcome_Vs_Launch.png)

![GraphVsDataviewAnalysis](/Resources/LaunchDate_Analysis.png)


### Challenges and Difficulties Encountered
* As a programmer, we look for the What, When, Why, Where and Who as part of the requirements. This exercise was very challenging as the HOW was defined. Especially it took me several debugging activities to determine the logical error in step 3d. As I was using a nested if to write the logic and following the direction in the 3d was setting a wrong index and resulting in wrong output. Since the suedo code was not very clear on to avoid nested if and step 2a & 2b asked to use For Loop was miss guiding the workflow and logical flow to be implemented.   

## Summary
  - Our returns are based on closing prices on the first and last market days of the year. Based on this data we may show postive or negative returns for a full year, however we would not know weekly/bi-weekly, monthly or quaterly trends. Just by looking at EOY returns will allow for portfolio changes yearly whereby missing out on some potential profits/limiting losses during shorter frequencies.
  - Having availability of hourly trends will also help in some profit taking during the day or potentailly readjusting portfolios
  
