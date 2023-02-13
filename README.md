Overview of the analysis: Explain the purpose of this analysis.
-The analysis in this challenge was to show the different cleaning and processing of a big data table from AWS database into a pyspark session, we first created a database structure in sql pgadmin and then i made different tables grouped by customer_id, selected columns, count grouped tables without duplicate, etc.

On the other hand, i created another session called Vine Review Analysis, i made the following tables:
Table filtered by total_votes equal or greater than 20
table filtered by the ratio of helpful votes by vine reviews greater than 0.5
table filtered by vine paid and unpaid
the total number of reviews in the vie reviews
a table filtered by the start rating of 5 and finally the percentage of the 5 star rating by the paid and unpaid vines.



Results: Using bulleted lists and images of DataFrames as support, address the following questions:

How many Vine reviews and non-Vine reviews were there?
-613 vine reviews
-64,968 non vine reviews


How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
-30,765 5-star reviews
-34,816 non 5-star reviews

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
-46.91% 5 stars
-56.08% non 5 stars
Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.


