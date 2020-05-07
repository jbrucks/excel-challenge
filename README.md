# excel-challenge
Using the Excel table provided, I was tasked to modify and analyze the data of 4,000 past Kickstarter projects to uncover market trends.

- Used conditional formatting, to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

- Created a new column called "Percent Funded" that uses a formula to uncover how much money a campaign made to reach its initial goal.

- Used conditional formatting to fill each cell in the "Percent Funded" column using a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.

- Created a new column called "Average Donation" that uses a formula to uncover how much each backer for the project paid on average.

- Created two new columns,"Category" and "Sub-Category", which use formulas to split the Category and Sub-Category column into two parts.

- Created a new sheet with a pivot table that will analyze the initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

- Created a stacked column pivot chart that can be filtered by country based on the table created.

- Created a new sheet with a pivot table that will analyze the initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

- Created a stacked column pivot chart that can be filtered by country and parent-category based on the table created.

- Created a new column named "Date Created Conversion" that will use this formula to convert the data contained within "launched_at" into Excel's date format.

- Created a new column named "Date Ended Conversion" that will use this formula to convert the data contained within "deadline" into Excel's date format.

- Recreate a new sheet with a pivot table with a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years.

- Created a pivot chart line graph that visualizes this new table.

- Created a new sheet with 8 columns:
  - Goal
  - Number Successful
  - Number Failed
  - Number Canceled
  - Total Projects
  - Percentage Successful
  - Percentage Failed
  - Percentage Canceled

- In the Goal column, create 12 rows with the following headers:
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

 - Using the COUNTIFS() formula, counted how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populate the Number Successful, Number Failed, and Number Canceled columns with this data.

 - Added up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a mathematical formula, found the percentage of projects that were successful, failed, or canceled per goal range.

 - Created a line chart that graphs the relationship between a goal's amount and its chances at success, failure, or cancellation.
