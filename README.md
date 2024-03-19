# Airborne Analytics: Navigating Customer Promotion Program

# Dashboard Link:https://app.powerbi.com/view?r=eyJrIjoiZmYxMGM4OGMtMmZiMC00NDA5LWIxOTEtYTI3YmI4OTk5ODVhIiwidCI6ImQzNWE5MjEwLTE3MzMtNGQ3My04NzlhLTJmOGQ3YWNkMTNhOCJ9&pageName=ReportSection

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

7- Created a measure to calculate the net loyalty members (start of the month) and running total of net loyalty members over time. These DAX measures were utilised in the visuals below.

 ![DAX1](https://github.com/bhumikadata/abcd/assets/131578649/efeac708-4ba5-48d2-af26-b1b7737a2a59)

 ![bar chart](https://github.com/bhumikadata/Airline-Loyalty-Program/assets/131578649/2f84e435-1afa-4f82-a3ea-c96b4b117e34)


8- Inserted line charts to show total enrollments and cancellations by month. This can be immensely helpful for the airline's leadership for indentifying trends in enrollment and cancellation patterns over time. 
  It will also help to montior performance by tracking enrollments and cancellations on a monthly basis to assess whether the program is attracting new customers effectively and retaining existing ones or if 
  there are issues leading to higher cancellation rates. 
 
 
 ![page1 line chart](https://github.com/bhumikadata/Airline-Loyalty-Program/assets/131578649/75573487-62f9-4c1d-9c6a-741c370c87fe)


9- Created measures to calculate flights booked by loyalty members (based on start of month) and flights booked by loyalty members the previous year which were utilized in visuals below.

 
 ![dax2](https://github.com/bhumikadata/Airline-Loyalty-Program/assets/131578649/8cfc236a-b375-4b0b-adb3-c5cc632ab557)

 ![dax3](https://github.com/bhumikadata/Airline-Loyalty-Program/assets/131578649/069ad485-dbd1-46a1-89e5-7b174957a3ae)

 ![flights booked](https://github.com/bhumikadata/Airline-Loyalty-Program/assets/131578649/167f5c18-61a0-4a4a-b907-bda18f309776)

10- Inserted a stacked column chart to show loyalty member flights booked by enrollment type, trended by month, and add a slicer to filter the page by enrollment type.

  ![stacked column](https://github.com/bhumikadata/Airline-Loyalty-Program/assets/131578649/d2948cdb-672c-4d1b-a8f8-dd60bef364dd)

  

# Results

Analyzing the year-over-year (YOY) trend from 2017 to 2018 and observing the impact of promotion activities on enrollments can provide valuable insights for Northern Lights Air's leadership. Here's how the observations can be interpreted:

# Overall YOY Trend:

From the comparison between 2017 and 2018, it's observed that there was an increase in enrollments, indicating a positive trend in the growth of the loyalty program.

# Impact of Promotion in 2018:

In 2018, the promotion activity had a significant impact on enrollments, leading to a substantial increase in the number of enrollments during the peak period. This spike in enrollments during the promotion period suggests that the promotion was effective in attracting new customers to the loyalty program.

# Comparison with Standard Enrollments:

When comparing enrollments in 2018 with and without the promotion activity, it's evident that the promotion contributed significantly to the overall increase in enrollments. The difference in enrollments during the promotion period (11,624) compared to the standard period highlights the effectiveness of the promotion in driving sign-ups.

# Effectiveness of Promotion:

The observed increase in enrollments during the promotion period had a subsequent impact on flights booked by loyalty members. This suggests that the promotion successfully attracted new customers to the loyalty program, leading to increased engagement and bookings.

# Long-Term Impact:

Although the promotion period saw a surge in enrollments and subsequent flight bookings, it's essential to monitor the long-term impact on customer retention and engagement. Leadership should assess whether the new sign-ups translate into loyal, repeat customers over time and continue to drive revenue for the airline.

# Impact of Churn Rate:

With a churn rate of 12%, it means that approximately 12% of the total loyalty program members discontinued their participation or canceled their memberships during the specified period. Monitoring the churn rate over time is crucial for understanding customer retention and loyalty.

# Strategic Implications:

Insights from the analysis can inform strategic decisions regarding future promotional activities, resource allocation, and marketing strategies. Leadership can leverage the success of the 2018 promotion to plan and execute similar campaigns in the future, while also considering the churn rate when planning future promotional activities and loyalty program initiatives.

In conclusion, analyzing the YOY trend and the impact of promotion activities provides Northern Lights Air's leadership with valuable insights into the effectiveness of their marketing strategies and helps guide future initiatives to drive customer acquisition, engagement, and loyalty.

