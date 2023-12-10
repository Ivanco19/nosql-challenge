# nosql-challenge

For this challenge, I will be evaluating various establishments across the United Kingdom in order to help their journalists and food critics decide where to focus future articles. During the process, I was notified that a new restaurant just opened and we need to add it to the database and take it into account for the analysis. You will be able to find 2 jupyter notebooks and one resources folder with a nonsql database inside of it.

First of all, you need to create a database on MongoDB called 'uk_food' and a collection named 'establishments'. Once they are created, you need to import the database on a json format by using the terminal. The code to import the database to mongo is located in the NoSQL_setup_starter jupyter notebook.

Also, on the NoSQL_setup_starter file you can see some basic queries to explore and analyze the data we currently have, like insert new data, update, and delete.

On the second jupyter notebook which is called NoSQL_analysis_starter, we explore some relevant data and prepare more complex queries that also requires coordenates and geographic locations, in order to know the most relevant establishments located nearby the new restaurant.

Finally, as results of the queries, I transform the data to a pandas dataframe for future analysis and visualizations.

-------------------------------------

This code was developed by Ivan Corona
