# Kickstarting with Excel
Click here to view the file that was used for this analysis project: [Kickstarter Analysis](https://github.com/vijaycse/kickstarter-analysis/blob/master/Kickstarter_Challenge.xlsx)

## Overview of Project
### Purpose
The purpose of this project is to is to compare the results of fundraising campaigns based on their launch dates and their funding goals. We specifically looked at the trends of theaters and plays to determine the successful, failed, and cancelled campaigns.

### Analysis of Outcomes Based on Launch Date
For the Outcomes Based on Launch Date, I created a pivot table that filtered the outcomes by category and the launch date. The columns display the status of the campaign, while the row shows the months during the campaign. This allows us to see the total count of successful, failed, and canceled theater campaigns. Below is an image of the pivot table with a filter for the theater category. 

![Theater Outcomes Pivot Table](https://github.com/vijaycse/kickstarter-analysis/blob/master/Resources/Theater%20Outcomes%20Pivot%20Table.PNG)

### Analysis of Outcomes Based on Goals
To analyze the Outcomes Based on Goals, I created a table that retrieved the total number of campaigns based off of certain criteria. In order to retrieve the correct count, the COUNTIFS statement was used. Within this formula, I set multiple criteria, including a range for the desired campaign goal, the specific category, and the outcomes of these campaigns. In this case, we wanted to look at the subcategory, plays.


## Results

### Outcomes Based on Launch Date Conclusions
From the line chart, we can see that the best month to start a theater campaign is in May as it produces the highest amount of successful outcomes. Similarly, we can infer that December would not be the best month to launch a theater campaign, as it has the lowest number of successful outcomes. In fact, the number of successful campaigns is almost equivalent to the number of failed campaigns during the month of December.

![Outcomes Based on Launch Date](https://github.com/vijaycse/kickstarter-analysis/blob/master/Resources/Theater_Outcomes_vs_Launch.png)

### Outcomes Based on Goals Conclusions
Although the pattern fluctuates, it is apparent that play campaigns with higher goals tend to have a greater percent chance of failing. We can see that there is a subtle decrease among campaign success as the goal amount becomes larger and larger. However, there is an anomaly at about $35,000, in which we see a sharp increase in the success rate and sharp decrease in failure rate. 

![Outcomes Based on Goals](https://github.com/vijaycse/kickstarter-analysis/blob/master/Resources/Outcomes_vs_Goals.png)
