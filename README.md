# Home_Sales
Challenge 22 big Data
Use SparkSQL to determine key metrics about home sales data. Create temporary views, partition the data,cache and uncache a temporary table, and verify that the table has been uncached.

1.	Used Spark to create a DataFrame from the dataset.
2.	Created temporary table of the original DataFrame. 
3.	written a query is that returns the average price, rounded to two decimal places, for a four-bedroom house that was sold in each year.
4.	written a query is that returns the average price, rounded to two decimal places, of a home that has three bedrooms and three bathrooms. 
5.	written a query isthat returns the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year built rounded to two decimal places. )
6.	written a query is that returns the view rating for the average price for homes that are greater than or equal to $350,000, rounded to two decimal places. (The output shows the run time for this query.)
7.	Created and validated a cache of the temporary "home_sales" table. 
8.	A partition of the home sales dataset by the "date_built" field is created, and the formatted parquet data is read.
9.	A temporary table of the parquet data is created. 
10.	The query from step 6 is run on the parquet temporary table, and the run time is computed.
11.	The "home_sales" temporary table is uncached and verified.
