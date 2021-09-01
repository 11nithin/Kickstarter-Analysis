# *Kickstarting with Excel*

## *Overview of Project*


### *Background and Purpose*
To find out how different campaigns are affetcted by their launch dates and their funding goals. Analysing the kickstarter dataset to find the outcomes based on the Launch date and outcomes based on Goals.



## *Analysis and Challenges*
We are using two analyses here "Analysis of Outcomes Based on Launch Date" and "Analysis of Outcomes Based on Goals"

### Analysis of Outcomes Based on Launch Date
To findout if the launch date has an impact on the campaign a pivot table is made that shows number of successful, failed and canceled outcomes based on months in "theatre" parent category. And line chart is created from the the pivot table

Pivot table

First, I created a pivot table from the Kickstarter worksheet, inorder to filter the pivot table by years. I created a column for "years" and extracted the year from the date created column.And in the pivot table placed Parent category and years under filter, Outcomes under columns, Date created under row, outcomes under values. Grouped the rows by month by selecting just months under group.This table shows the number of successful, failed and canceled outcomes under theatre parent category.

Line chart

Using the pivot table created a line chart. Line chart give a better visualization of our data. 


### Analysis of Outcomes Based on Goals
To analyse the outcomes based on goal created a table using COUNTIFS formula and found the number of successful, failed and canceled outcomes in each range and found the percentage of success rate for each range. Line chart is created with range of goal on X axis and Percentages on Y axis.


![outcomebasedongoal](https://github.com/11nithin/Kickstarter-Analysis/blob/main/Resources/Outcomes%20based%20on%20Goals.PNG)

### Challenges and Difficulties Encountered
Biggest challenge and difficulties encountered was when using the COUNTIF formula. After copying the formula from the first cell. I had to go to each cell and change the goal range. If we had the goal ranges in 100 row it would have been a tedious job. 



## *Results*

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Based on the data “May” has the greatest number of successful outcomes. October, November and December have the number of successful roughly equals to number of failed. 

- What can you conclude about the Outcomes based on Goals?

Based on the outcomes based on goal data. Goal with amount less than $5000 have the highest success rate. But the goal has no big impact on the outcome. Goal $25,000 to $35,000 success rate is much lesser than the goal $35,000 to $45,000

- What are some limitations of this dataset?

This dataset doesn’t show what group of people (age, sex etc.) are contributing to each category. That would be beneficial data for future campaigns

- What are some other possible tables and/or graphs that we could create?

It would be also good to know how many days a campaign ran. We can identify average number of days for a successful campaign based on the goal. 

