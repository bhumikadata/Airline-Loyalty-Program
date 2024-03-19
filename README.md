# Airborne Analytics: Navigating Customer Promotion Program

## Dashboard Link: https://app.powerbi.com/groups/me/reports/52e4493a-6a9e-4409-ac83-35f397a7ccc5/ReportSection?experience=power-bi

# Problem

For our dashboard we will analyze the loyalty promotion program ran by a hypothetical airline company Northern Lights Air (NLA). It ran the program from 1st Feb - 30th April 2018, offering 1.5x loyalty card points to new member for flights booked through the remainder of the year.

# Objective

The NLA leadership wants to analyze loyalty engagement enrollemnts, cancellations and flights booked.

# Steps Followed

1- Explored and QA the data and ensured columns and data type as accurate.

2- Added Column to the Customer Loyalty History Table to calculate the enrollemnt start of the month and cancellations start of the month.

3- Added a column to Customer Flight Activity Table to calculate flights booked start of the month.

4- Added a binary column to Customer Loyalty History Table to flag if the customer has canceled.

5- Build a data model to connect the calender, Customer Flight Activity and Customer Loyalty History table through all the 'start of month' fields.

6- Create DAX measures to calculate total enrollments (based on loyalty number) and total flights booked.



