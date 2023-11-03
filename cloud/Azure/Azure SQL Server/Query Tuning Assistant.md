The Query Tuning Assistant (QTA) uses the data captured by the Query Store to find queries 
that are beginning to regress. 
The QTA automatically experiments to find a solution that will speed up the query before 
it underperforms to the point of affecting users. 
You can use the Query Store and the QTA to monitor your database after upgrading. 
After migrating a database to SQL Server 2016 or higher, leave the compatibility level 
of the database unchanged, then enable Query Store. 
It collects query performance statistics you'll use as a baseline. When you then change 
the compatibility level, you know if each query is doing better, equally, or worse than before.

When the compatibility level is moved to upgrade the database, SQL Server changes the version of the cardinality estimator that's used. The QTA can find possible patterns of query regression because of the change in cardinality estimator, and experiments to find performance improvements. You can then create plan guides for those queries that showed improvement.

The Query Store continuously measures the performance statistics of your queries, just as an aircraft's flight data recorder captures activity. When something goes wrong, there's a history of information to discover the cause of the problem. The Query Store can be enabled on any database on SQL Server 2016 or higher, whatever the compatibility level. Use the Query Store to continuously monitor query performance, and for A/B testing where you measure the outcome of a single change.
