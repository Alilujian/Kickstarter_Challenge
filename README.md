# Kickstarter_Challenge
Analysis of the kickstarter data in Excel

## Overview of Project
Kickstarter is crowdfunding platform help bring projects to life. There are many projects launched on Kickstarter, but not every project has made success. What makes crowdfunding successful is a question that all promoters want to know the answer to. 


### Purpose
The purpose of this project is to analysis crowdfunding data to determine:
1. the relationship between launch dates and the outcomes.
2. the relationship between funding goals and the campaign outcomes.

## Data
The Kickstarter dataset is an Excel spreadsheet that contains column like project names, funding goals, category, campaign outcomes and the start/end date, etc.

### Create New Column
1. Some of the campaign failed simly becase they missed a very small amount from the goals. In order to see how successful the project was, the percentage funded would be more straight forward. A new column percentage funded will be created.
2. From the column Category and Sub-category, we can't clearly determine the sub-categroy of plays by looking at this column. In order to read the category clearly, we split the column into two new column, parent category and sub-category.
3. Since the dataset only shows us the Unix timestamps, we need to convert the launched_at coulmns into a readable datetime information. In this case, we will create a new column "Date Created Conversion".

## Analysis and Challenges
In this project, we are dealing with tabular data which is displaed in a column and row format. It is hard for us to analysis the dataset comprehensive without using tools like filter, pivot table, and chart. The challenges for me is to use the advanced tools that is built in the Excel software.

### Analysis of Outcomes Based on Launch Date
Based on launch date, most successful campaign lauch in May and June. In December, the difference between the number of successful and failed campaign was not significant. Generally speaking, the most crowdfunding lauched in May, and the least lauched in December.
![Theater_Outcomes_vs_Launch](https://github.com/Alilujian/Kickstarter_Challenge/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Based on the funding goals, most of the campaign has set the funding goals less than $9999. The number of campaign is smaller with higher funding goals. As the lower goals campaign, the percentage of success and failed was similar (around 50%).
![Outcomes_vs_Goals](https://github.com/Alilujian/Kickstarter_Challenge/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
One of the problems I encountered was how to use the countifs function. When putting the 3 criteria into the function, I forgot to lock the column when choosing range, which caused an error when pulling down the function. I ended up adding the lock symbol ($) before the column letter and solved the problem.\
By completing this project, i became familiar with the COUNTIFS funtion in Excel. 

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?\
In conclusions, the campaign are most successful in May. In December, the successful and failed outcomes are at the same level. Canceled outcomes are similar over 12 months.

- What can you conclude about the Outcomes based on Goals?\
At lower goals, the successful and failed outcomes are at a similar level. With higher goals, the percentage successful is higher than the percentage failed. The number of projects are higher with lower goals compare to projects with higher goals.

- What are some limitations of this dataset?\
1. The dataset only contain data from 2009 to 2017, which means the dataset is out of date. The results we got from this dataset might not be accurate.
2. It is better to konw the time spend on Louise campaign. So that we can compare the relationship between campaign duration and the outcomes.

- What are some other possible tables and/or graphs that we could create?\
We can also creates chart like average donation versus subcategory. From this chart we would be able to see which category people would like to fund.
