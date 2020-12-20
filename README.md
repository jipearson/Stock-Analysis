# Stock-Analysis

## Overview of Project
Refactor our code used to analyze the small stock market dataset in Module 2 to run more efficiently so that it can be used to analyze stock volumes and returns on larger datasets quickly. 
### Purpose
Determining if refactoring our code made it run more efficiently. 
## Analysis

### Analysis of efficiency gained by refactoring 

- Refactored Code
  - ![](Resources/VBA_Challenge_2017.png) ![](Resources/VBA_Challenge_2018.png)
- Original Code
  - ![](Resources/OC_2017.png) ![](Resources/OC_2018.png)
  
The graphics above show the execution times of both the original code and the refactored code. The refactored code ran 86.5% and 85.9% more efficiently for 2017 and 2018 respectively. 

### Analysis of Stock Performance


The graphics below show the total trade volumes and the % return for the individual "green" stocks in 2017 and 2018.

![](Resources/StockPerformance_2017.png)
![](Resources/StockPerformance_2018.png)
The "Outcomes Based on Goal" graphic above shows that the campaigns with the highest rate of success are in the found within the two lowest goal buckets (76% and 73% respectively). Although there is an elevated rate of success for the 35k-40k and 40k-45k buckets, the volumes are too low (see "Goal Volumes and Outcomes" chart above) to draw any meaningful conclusions. 
### Challenges and Difficulties Encountered
Although there were minimal issues faced performing this analysis, the volume issue stated above can makes it difficult to make confident recommendations based on more granular criteria elements. 
## Results

- Outcomes based on Launch Date conclusions.
  - Months with higher volumes of launched campaigns tend to have higher success rates. 
  - Even though May typically has the highest volume of new campaign launches it is still the most attractive month from a rate of success standpoint. 

- Outcomes based on Goals conclusions. 
  - We generally see a deterioration in the rate of successs as the campaign goal increases (again - difficult to extract meaningful conclusions from the higher goal buckets)
  - While only 31% of campaigns have a goal greater than 5k the same population accounts for nearly 46% of failed campaigns.  

- Dataset limitations.
  - There are relatively few records in the data which makes it difficult to disect more granular categories. 
  - We have no way to measure elements not listed in the data set, specifically the visual factors that help determine a campaigns success/failure. 
  
- What are some other possible tables and/or graphs that we could create?
  - Layer both goals and launch dates to see if the results change significantly when working in tandem.  
  - Determine success rates based on the campaign funding window (difference between the date created and the date ended) and visulaize the results on a line chart. 
