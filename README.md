Answering-Business-Questions-using-SQL
====================================================

Creating Helper Functions(Step 1)
----------------------------------------------------
1. Import the SQLite, pandas and matplotlib modules, and use the magic command `%matplotlib` inline to make sure any plots render in the notebook.<br>
2. Create a `run_query()` function, that takes a SQL query as an argument and returns a pandas dataframe of that query.<br>
3. Create a `run_command()` function that takes a SQL command as an argument and executes it using the sqlite module.<br>
4. Create a `show_tables()` function that calls the `run_query()` function to return a list of all tables and views in the database.<br>
5. Run the `show_tables()` function.<br>

Selecting Albums to Purchase(Step 2)
----------------------------------------------------
1. Write a query that returns each genre, with the number of tracks sold in absolute numbers and in percentages.<br>
2. Create a plot to show this data.<br>
3. Write a paragraph that interprets the data and makes a recommendation for the three artists whose albums we should purchase for the store, based on sales of tracks from their genres.<br>

Analyzing Employee Sales Performance(Step 3)
----------------------------------------------------
1. Write a query that finds the total dollar amount of sales assigned to each sales support agent within the company. Add any extra attributes for that employee that you find are relevant to the analysis.<br>
2. Create a plot of the results of your query.<br>
3. Write a short statement describing your results, and providing a possible interpretation.<br>

Analyzing Sales by Country(Step 4)
----------------------------------------------------
1. Write a query that collates data on purchases from different countries. For each country, include:<br>
* total number of customers
* total value of sales
* average value of sales per customer
* average order value
2. Where a country has only one customer, collect them into an "Other" group.<br>
3. The results should be sorted by the total sales from highest to lowest, with the "Other" group at the very bottom.<br>

Visualizing Sales by Country(Step 5)
----------------------------------------------------
For each dimension, create a visualization which demonstrates the data we collated in the previous step.<br>
* You should decide whether the "Other" group is relevant to your analysis and make decisions on where to include it (if anywhere) in your visualizations.
Write a few sentences interpreting your data and visualizations, and make one or more recommendations to the marketing team on which countries have potential for growth.<br>

Albums vs Individual Tracks(Step 6)
-----------------------------------------------------
Write a query that categorizes each invoice as either an album purchase or not, and calculates the following summary statistics:<br>
* Number of invoices
* Percentage of invoices
Write one to two sentences explaining your findings, and making a prospective recommendation on whether the Chinook store should continue to buy full albums from record companies<br>
