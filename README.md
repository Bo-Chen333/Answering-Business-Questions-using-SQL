Answering-Business-Questions-using-SQL
====================================================

Creating Helper Functions(Step 1)
----------------------------------------------------
Import the SQLite, pandas and matplotlib modules, and use the magic command `%matplotlib` inline to make sure any plots render in the notebook.<br>
Create a `run_query()` function, that takes a SQL query as an argument and returns a pandas dataframe of that query.<br>
Create a `run_command()` function that takes a SQL command as an argument and executes it using the sqlite module.<br>
Create a `show_tables()` function that calls the `run_query()` function to return a list of all tables and views in the database.<br>
Run the `show_tables()` function.<br>
