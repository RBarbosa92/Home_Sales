PySpark SQL Home Sales Big Data Project
This project employs PySpark and Spark SQL within the Google Colab environment to extract essential insights from home sales data. The process involves creating temporary views, partitioning data, and managing the caching and uncaching of a temporary table using Spark.

For instance, I established a table featuring two columns. One column displays the average price, rounded to two decimal places, specifically for four-bedroom homes in the database. The second column showcases the years grouped by the sale of each property. Additionally, I conducted runtime comparisons for queries on an uncached temporary table, a cached temporary table, and a cached and partitioned temporary table with Parquet.

Key Metrics Explored
Several key metric questions were addressed during the analysis, including:

Determining the average price for a four-bedroom house sold in each year.
Calculating the average price of homes for each year they were built, focusing on those with three bedrooms and three bathrooms.
Evaluating the average price of homes for each year, considering those with three bedrooms, three bathrooms, two floors, and a size greater than or equal to 2,000 square feet.
Assessing the "view" rating for homes priced at or above $350,000.
