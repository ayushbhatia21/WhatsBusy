# WhatsBusy
DEMONSTRATION:

Challenge 1:

The class MoneyBox performs the functions of a virtual money box. 
Init function initializes the box with a capacity and the variable u, which stores the number of coins, is initialized as 0. 
The function can_add checks if the virtual box has the capacity to add v more coins.
The add function adds v coins to the virtual Money box if there's any capacity left.

Challenge 2:

The table_1 contains both the foreign keys - id_manager and id_employee. These keys were used to extract first name and last name from the manager and employee table. Then UNION was used to join both the queries.

Challenge 3:

For part a), I used the aggregate and groupby function to store the mean, median, max and min values as separate columns.
For part b), I calculated the maximum and minumum amount for each employee number using the agg() and groupby() function. Then, I created a new dataframe to store the difference of these two values and extracted the first 2 rows from that dataframe.

Challenge 4:
The given dataset is a time-series data with the value of number of visitors from the years 2000 to 2009, for each day. So, I transformed the data to store the average or mean daily value for each month for all the ten years. Then, I visualized the trend, that came out to be seasonal. So, I used the Seasonal ARIMA time series model and extracted the best parameters to fit the model. And finally, I used the forecast function to get the estimate number of visitors for the next day.



