# Kickstarter_Challenge
Analysis of the kickstarter data in Excel

## Overview of Project
Excle is a powerful tool for data analysis, visulization, and organization.
In this project we will using the Excel tools to help the playwright Louise on her crowd funding campaign.

### Purpose
The purpose of this project is to analysis crowdfunding data to determine:\
1. the relationship between launch dates and the outcomes.
2. the relationship between funding goals and the campaign outcomes.

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
The dataset only contain data from 2009 to 2017, which means the dataset is out of date. The results we got from this dataset might not be accurate.

- What are some other possible tables and/or graphs that we could create?\
We can also creates chart like average donation versus subcategory. From this chart we would be able to see which category people would like to fund.
