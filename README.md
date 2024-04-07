# Home_Sales

# Data Modeling
* Worked with a tutor to complete this assignment.
* Used `home_sales_revised.csv` to create the temporary table, `home_sales`.

1. Utilized SparkSQL to determine the following :
* Note - all values were rounded to two decimal places.

    a. The average price of a four-bedroom house sold for each year.

    b. The average price of a home for each year the home was built, that has three befrooms and three bathrooms.

    c. The average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 feet.

    d. The average price of a home per "view" rating with an average home price greater than or equal to $350,000.

# Data Engineering
1. Cached the data from the last query. 

2. Partitioned the last query by the "date_built" field on the formatted parquet home sales data.

3. Created a temporary table for the parquet data and ran the last query.

4. Uncached the `home_sales` table and verified it was uncached.

# Data Analysis
* Runtime using cached data of the last query was approximately 25% faster than the uncached runtime.

* Runtime using parquet data of the last query was nearly identical to the uncached runtime.
