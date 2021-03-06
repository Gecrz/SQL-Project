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

* Using hvPlot, create a line plot representing the time series of transactions over the course of the year for each cardholder. In order to compare the patterns of both cardholders, create a line plot containing both lines.

  * What difference do you observe between the consumption patterns? Does the difference suggest a fraudulent transaction? Explain your rationale.

* The CEO of the firm's biggest customer suspects that someone has used her corporate credit card without authorization in the first quarter of 2018 to pay for several expensive restaurant bills. You are asked to find any anomalous transactions during that period.

  * Using Plotly Express, create a series of six box plots, one for each month, in order to identify how many outliers there are per month for cardholder ID 25.

  * Do you notice any anomalies? Describe your observations and conclusions.
  
  
  ## Challenge

Another approach to identify fraudulent transactions is to look for outliers in the data. Standard deviation or quartiles are often used to detect outliers.

# These materials below helped us understand and maximize this process 

* [How to Calculate Outliers](https://www.wikihow.com/Calculate-Outliers)

* [Removing Outliers Using Standard Deviation in Python](https://www.kdnuggets.com/2017/02/removing-outliers-standard-deviation-python.html)

* [How to Use Statistics to Identify Outliers in Data](https://machinelearningmastery.com/how-to-use-statistics-to-identify-outliers-in-data/)


