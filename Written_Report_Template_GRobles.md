# Kickstarting with Excel

## Overview of Project
The project consisted of two parts. In part one of the project, we had to use our knowledge of pivot tables and graphing in Excel to visualize campaign outcomes based on launch date. In part two of the project, we had to use our Excel skills to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. 

### Purpose
Part one of project was to visualize campaign outcomes based on launch date. Part two of project was to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount.

## Analysis and Challenges
The challenge was to clean up the data in a way that could be used to analyze it and help visualize the story we were trying to tell.  First, we had to convert the dates from Epoch to normal date format before we could work with the data.

### Analysis of Outcomes Based on Launch Date
From the resulting line graph, we can see that May was the most successful month for launch dates and that December was the least successful month.  We can also gather that the number of cancelations throughout the year was relatively low.

### Analysis of Outcomes Based on Goals
From the resulting line graph, we notice that there were no plays cancelations and that the relationship between percentage of successful and percentage of failed goals had an inverse affect.  The percent of goals with the most success also had the least failure and visa versa. But the graph did not illustrate which goal amounts had the highest projects whether successful or failed.

### Challenges and Difficulties Encountered
One challenge was the need to use the iferror function due to there being no cancelations. Dividing by zero gives an error message that needed to be fixed. A difficulty for me was writing the countifs statement with relation to the greater than and less than portion.  I needed help from the Learning Assistant.  I almost had it right, just needed to tweak my formula a little.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1.May and June are good months for launching theater. Looking at the data, those two months 									have the highest number of theater launching, whether successful or failed.
2.The number of theater cancelations is relatively low all year long.

- What can you conclude about the Outcomes based on Goals?
1.The highest number of plays usually have a goal between 1000 to 4999 for a total project of 534 plays.
2.Plays with less than 4999 goal tend to be most successful plays.

- What are some limitations of this dataset?
1.We do not know the age group of the people that go to the plays.
2.We do not know the sex of the people that attend these plays.
3.We do not know who contributed or pledged.
4.Those data set were not collected or shown in the Kickstarter sheet. That data could be useful when deciding who to target for additional revenue or when marketing the plays.

- What are some other possible tables and/or graphs that we could create?
1.We can create a graph that shows the relationship between goals and pledged amounts.
2.We can also create a graph of that demonstrates the number of plays by country.
3.We can also look at the other subcategories, such as television, classical music or animations for example.
