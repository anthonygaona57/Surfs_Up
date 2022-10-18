# Surfs_Up
Overview of Analysis:
The purpose of the Surfs Up challenge is to use Python, Pandas, and SQLAlchemy in order to write an analysis that can show the temperatures on Oahu for the month of June and December. This analysis will be used in order to find the profitability of the surf season, whether ice cream sales could have any similarites and to determine whether the business can be running year round. The method in this analysis is needed for the date column in the measurements table of the Hawaii.sqlite database to be filtered on the month. A new dataframe ends up being created to hold the new data for summary statistics calculations.


Results:
June:
•	Count – 1700
•	Mean- 74.94
•	Standard deviation- 3.26
•	Min- 64
•	25%- 73
•	50%-75
•	75%- 77
•	Max- 85



December:
•	Count- 1517
•	Mean- 71.04
•	Standard Deviation- 3.75
•	Min- 56
•	25% - 69
•	50%- 71
•	75%- 74
•	Max- 83
 


Summary:
The analysis states that the standard deviation of temperatures in December is greater than that of June. This means the temperature fluctuates more during that month. One query I identified is precipitation values to determine which locations are more hospitable for an ice cream business. We could look at the standard deviation of each specific location during the month to understand which locations are more acceptable for a business. The lower the standard deviation would indicate a location experiences stable temperatures which would likely increase ice cream sales due to more fluctionaly temperatures. 


