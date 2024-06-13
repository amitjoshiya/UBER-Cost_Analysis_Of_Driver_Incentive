Overview
This project aims to analyze and determine the cost-effectiveness of two bonus options for Uber drivers in Chennai during the IPL 2024 event on May 26th. The goal is to help Uber's Driver Partner Ops team decide which bonus option is more efficient in terms of cost.

Dataset
The dataset contains performance metrics of Uber drivers during the specified time frame. Each row represents the performance of an individual driver.

Dataset Columns
driver_id: Unique identifier for each driver.
online_hours: Number of hours the driver was online.
acceptance_rate: Percentage of ride requests the driver accepted.
completed_trips: Number of trips the driver completed.
rating: Average rating of the driver during the time frame.
Example Data
driver_id	online_hours	acceptance_rate	completed_trips	rating
1	9	0.95	11	4.8
2	8	0.88	10	4.7
3	10	0.92	12	4.9
Analysis Objectives
The main objective is to compare the costs associated with the two bonus options:

Option 1: Rs. 3000 for each driver meeting the following criteria:

Online for at least 8 hours
Acceptance rate of at least 90%
Completed at least 10 trips
Rating of 4.7 or better
Option 2: Rs. 250 per trip for all drivers who meet the following criteria:

Completed at least 12 trips
Rating of 4.7 or better
Analysis Steps
Filter Drivers Meeting Option 1 Criteria:

Online hours ≥ 8
Acceptance rate ≥ 90%
Completed trips ≥ 10
Rating ≥ 4.7
Filter Drivers Meeting Option 2 Criteria:

Completed trips ≥ 12
Rating ≥ 4.7
Calculate Total Cost for Option 1:

Count the number of drivers meeting Option 1 criteria.
Multiply the count by Rs. 3000.
Calculate Total Cost for Option 2:

Sum the number of trips for drivers meeting Option 2 criteria.
Multiply the total number of trips by Rs. 250.
Compare the Total Costs:

Determine which option has a lower total cost.

Conclusion
This project provides a comprehensive analysis to determine the more cost-effective bonus option for Uber drivers in Chennai during the IPL 2024 event. By following the steps and utilizing the provided code, you can replicate the analysis and help make data-driven decisions.

For any questions or further assistance, please contact the Data Science team at Uber.
