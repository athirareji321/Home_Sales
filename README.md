# Home_Sales

# Home_Sales

### OBJECTIVES
- To use your knowledge of SparkSQL to determine key metrics about home sales data. 

- Then use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

### RESULTS

- A Spark DataFrame was created from the provided dataset.

- A temporary table based on the original DataFrame was established for analysis.

- A query was executed to calculate the average price of four-bedroom houses sold in each year, rounding the results to two decimal places.

- A query was formulated to determine the average price of homes with three bedrooms and three bathrooms, rounding the result to two decimal places.

- A query was written to compute the average price of homes with three bedrooms, three bathrooms, two floors, and a minimum size of 2,000 square feet for each year built, rounding the average price to two decimal places.

- A query was developed to find the view rating associated with the average price of homes valued at $350,000 or more, with the average price rounded to two decimal places. The run time for this query was also recorded.

- A cache of the temporary "home_sales" table was created and validated to improve query performance.

- The query from step 6 was re-run on the cached "home_sales" table, and the run time was measured for performance assessment.

- A partition of the home sales dataset by the "date_built" field was created, and the data was stored in a formatted parquet file.

- A temporary table was then created from the parquet data for further analysis.

- The query from step 6 was executed on the temporary table created from the parquet data, and the run time was noted for comparison.

- Finally, the "home_sales" temporary table was uncached, and this operation was verified for proper resource management.





