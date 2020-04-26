# Excel Data Analytics

## Background
Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. For this week's homework, you will organize and analyze a database of 4,000 past projects in order to uncover any hidden trends.

## Task
Using the Excel table provided, modify and analyze the data of 4,000 past Kickstarter projects as you attempt to uncover some market trends.

Use conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

Create a new column O called Percent Funded that uses a formula to uncover how much money a campaign made to reach its initial goal.

Use conditional formatting to fill each cell in the Percent Funded column using a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.

Create a new column P called Average Donation that uses a formula to uncover how much each backer for the project paid on average.

Create two new columns, one called Category at Q and another called Sub-Category at R, which use formulas to split the Category and Sub-Category column into two parts.

The dates stored within the deadline and launched_at columns use Unix timestamps. Fortunately for us, there is a formula that can be used to convert these timestamps to a normal date.

Create a new column named Date Created Conversion that will use this formula to convert the data contained within launched_at into Excel's date format.

Create a new column named Date Ended Conversion that will use this formula to convert the data contained within deadline into Excel's date format.


## Result
![FullTable](https://github.com/ovinueza/Excel_DataAnalytics/blob/master/images/FullTable.png)

![CategoryStats](https://github.com/ovinueza/Excel_DataAnalytics/blob/master/images/CategoryStats.png)

![SubCategoryStats](https://github.com/ovinueza/Excel_DataAnalytics/blob/master/images/SubcategoryStats.png)

![LauchDateOutcomes](https://github.com/ovinueza/Excel_DataAnalytics/blob/master/images/LaunchDateOutcomes.png)

![GoalOutcomes](https://github.com/ovinueza/Excel_DataAnalytics/blob/master/images/GoalOutcomes.png)

![backers01](https://github.com/ovinueza/Excel_DataAnalytics/blob/master/images/backers01.png)
