# SQL-Project

### Data Modeling

Create an entity relationship diagram (ERD) by inspecting the provided CSV files.

**Note:** For the `credit_card` table, the `card` column will be a VARCHAR(20) datatype rather than an INT.

Part of the challenge here is to figure out how many tables you should create, as well as what kind of relationships you need to define among the tables.

### Data Engineering

Using your database model as a blueprint, we will create a database schema for each of your tables and relationships. Specify data types, primary keys, foreign keys, and any other constraints you defined.

After creating the database schema, we imported the data from the corresponding CSV files.

### Data Analysis

Now that our data is prepared within the database, it's finally time to identify fraudulent transactions using SQL and Pandas DataFrames. In this part of the project, we will analyze the data and then create a report within a Jupyter Notebook file to present your findings. Our report should answer the following questions:

* How can you isolate (or group) the transactions of each cardholder?

* Consider the time period 7:00 a.m. to 9:00 a.m.

  * What are the 100 highest transactions during this time period?

  * Do you see any fraudulent or anomalous transactions?

  * If you answered yes to the previous question, explain why you think there might be fraudulent transactions during this time frame.

* Some fraudsters hack a credit card by making several small payments (generally less than $2.00), which are typically ignored by cardholders. Count the transactions that are less than $2.00 per cardholder. Is there any evidence to suggest that a credit card has been hacked? Explain your rationale.

* What are the top five merchants prone to being hacked using small transactions?

* Once you have a query that can be reused, create a view for each of the previous queries.
