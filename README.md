# Excel-Challenge
![image](https://github.com/nasr9000/Homework-File/assets/128746625/830e20e4-0bf0-443e-bcef-3a0d85a311cc)
![image](https://github.com/nasr9000/Homework-File/assets/128746625/5ff5d257-98ed-4b80-b8ac-e1a61500b3c5)


About

In this challenge, small startup businesses and crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. 
We analyzed various different metrics across these businesses such as the percent funded, country of operations, currency, and the business category and subcategory.
Using excel pivot tables, excel formulas, and conditional formatting our job was to measure these columns of data and uncover any hidden trends that may or may not have led to their success/failures. 
The bulk of our analysis came from the end where we gathered all of the data and created two forms of analysis. The first was our Crowdfunding Goal Analysis, which consisted of 8 columns measuring the outcomes of the crowdfunding startups. Second, was the Statistical Analysis portion which allowed us to summarize our findings and come to a broader conclusion. 
To say the trends that are displayed through our charts/graphs uncover any groundbreaking concrete findings is a bit of an overstatement as the trends remain inconsistent and the data itself is limited to external factors not present in this dataset. However, being able to see the outcomes of each project that these 
startups began was very telling in many other ways such as how funding may not entirely affect business efficiency or maybe how industry popularity can also have a role in business/ project performance.
This challenge as an introduction to data analytics that was not necessarily conclusive but it was fun and exciting to see how data can be used in many versatile ways. 



Using the Excel workbook in your .zip file, modify and analyze the sample-project data and try to uncover market trends.

![image](https://github.com/nasr9000/Homework-File/assets/128746625/c2198f0d-6c85-4816-b916-58ce2b9217d7)


Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.

Use conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.

Create a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.

Use conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale should start at 0 with a dark shade of red, and it should transition to green at 100 and blue at 200.

Create a new column called Average Donation that uses a formula to find how much each project backer paid on average.

Create two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.

![image](https://github.com/nasr9000/Homework-File/assets/128746625/b35451b4-6222-4e4a-96ca-0c35ef5c0d64)


Create a new sheet with a pivot table that analyzes your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.


Create a stacked-column pivot chart that can be filtered by country based on the table that you created.

![image](https://github.com/nasr9000/Homework-File/assets/128746625/cc708216-4abf-42ed-a49e-bea61c35f0d8)

- Create a new sheet with a pivot table that analyzes your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.
- Create a stacked-column pivot chart that can be filtered by country and parent category based on the table that you created
- The dates in the deadline and launched_at columns use Unix timestamps. Fortunately for us, this formula that can be used to convert these timestamps to a normal date.
- Create a new column named Date Created Conversion that will use this formula to convert the data contained in launched_at into Excel's date format.
- Create a new column named Date Ended Conversion that will use this formula to convert the data contained in deadline into Excel's date format.

![image](https://github.com/nasr9000/Homework-File/assets/128746625/badcd2e3-2de0-4ab0-bab0-2975cf68b510)

- Create a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years.
- Now, create a pivot-chart line graph that visualizes this new table.




Create a report in Microsoft Word, and answer the following questions:


Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?


What are some limitations of this dataset?


What are some other possible tables and/or graphs that we could create, and what additional value would they provide?





Crowfunding Goal Analysis


Create a new sheet with 8 columns:
1. Goal
2. Number Successful
3. Number Failed
4. Number Canceled
5. Total Projects
6. Percentage Successful
7. Percentage Failed
8. Percentage Canceled


In the Goal column, create 12 rows with the following headers:
- Less than 1000
- 1000 to 4999
- 5000 to 9999
- 10000 to 14999
- 15000 to 19999
- 20000 to 24999
- 25000 to 29999
- 30000 to 34999
- 35000 to 39999
- 40000 to 44999
- 45000 to 49999
- Greater than or equal to 50000

![image](https://github.com/nasr9000/Homework-File/assets/128746625/8acda0ed-4a73-45aa-a9af-c014a01756d3)


- Using the COUNTIFS() formula, count how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populate the Number Successful, Number Failed, and Number Canceled columns with these data points.
- Add up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a   mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.
- Create a line chart that graphs the relationship between a goal amount and its chances of success, failure, or cancellation.


Statistical Analysis
Most people would use the number of campaign backers to assess the success of a crowdfunding campaign. Creating a summary statistics table is one of the most efficient ways that data scientists can characterize quantitative metrics, such as the number of campaign backers.
For gaining an in-depth understanding of campaign backers, evaluate the number of backers of successful and unsuccessful campaigns by creating your own summary statistics table.

Create a new worksheet in your workbook, and create one column for the number of backers of successful campaigns and one column for unsuccessful campaigns.

![image](https://github.com/nasr9000/Homework-File/assets/128746625/20dd5e04-c65d-4f7a-858b-ee8a562c14b7)

Use Excel to evaluate the following values for successful campaigns, and then do the same for unsuccessful campaigns:

1. The mean number of backers2.
2. The median number of backers
3. The minimum number of backers
4. The maximum number of backers
5. The variance of the number of backers
6. The standard deviation of the number of backers
7. Use your data to determine whether the mean or the median better summarizes the data.
8. Use your data to determine if there is more variability with successful or unsuccessful campaigns. Does this make sense? Why or why not?
