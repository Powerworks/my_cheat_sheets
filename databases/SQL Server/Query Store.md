The Query Store feature was introduced in SQL Server 2016 
to continuously collect information about the execution and performance of queries 
within a database. It operates like a flight data recorder, by gathering runtime information on queries and plans. If you save this runtime data, you can track performance over time. By default, the Query Store isn't enabled on a database, but any database on an instance of SQL Server 2016 or higher can take advantage of it. This advantage includes databases with an earlier compatibility level than the instance. If you migrate a database from SQL Server 2012 to SQL Server 2019 and leave the compatibility level at 110, Query Store can still operate on the database.

After enabling the Query Store on a database, statistics are gathered for your queries 
and categorized as:


Regressed Queries
Overall Resource Consumption
Top Resource Consuming Queries
Queries with Forced Plans
Queries with High Variation
Tracked Queries


A regressed query occurs when the query optimizer uses a different query plan that causes the 
performance to degrade. This regression happens after an important change, like adding a new index, 
a dropped or altered index, an update to the statistics, or a change in the data cardinality. 
Before Query Store, identifying the issue was a problem for database developers and administrators, 
as SQL Server provided no insight into the cause. However, you can use the Query Store to find regressed queries and force the optimizer to use a particular plan from history.

