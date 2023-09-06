This example Excel workbook analyzes over 1000 sample projects from Crowdfunding platforms like Kickstarter and Indiegogo. 

Highlights:

Use conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.

Create a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.

Use conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale should start at 0 with a dark shade of red, and it should transition to green at 100 and blue at 200.

Create a new column called Average Donation that uses a formula to find how much each project backer paid on average.

Create two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.

Create a new sheet with a pivot table that analyzes your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

Create a stacked-column pivot chart that can be filtered by country based on the table that you created.

The dates in the deadline and launched_at columns use Unix timestamps, an Excel formula is used to convert these timestamps to a normal date.

Using the COUNTIFS() formula, count how many successful, failed, and canceled projects were created with goals within a given range. Populate the Number Successful, Number Failed, and Number Canceled columns with these data points.

Create a line chart that graphs the relationship between a goal amount and its chances of success, failure, or cancellation.

Use Excel to evaluate the following values for successful campaigns:

The mean number of backers
The median number of backers
The minimum number of backers
The maximum number of backers
The variance of the number of backers
The standard deviation of the number of backers
