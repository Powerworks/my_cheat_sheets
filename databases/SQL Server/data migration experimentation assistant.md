Although DMEA is for A/B testing,
The Database Experimentation Assistant (DEA) enables you to automate the process of testing the workload of your current database on a target server. 

In practice, a server may have developers and DBAs constantly making changes. When a query slows down, it can be difficult to pinpoint the change that causes the degradation. When testing your database on an upgraded version, you can create the new database and replay a sample of the current workload on the upgraded database using DEA.

DEA compares a source and target database that are identical except for one variation: the upgraded database. You run a trace on your source production server to capture the queries that form a typical workload. Running the trace has a minimal impact on the server, so you can run tracing even during heavy demand periods. The DEA tool finds degraded queries and generates drill-through reports to highlight code that runs slower in the target environment. You can then optimize the code before you switch your production system to the target database.

The DEA tool reduces administrative time and eliminates human error, 
by automating much of the testing process after you've upgraded your databases. 

By generating an analysis report that highlights query errors, query plan information, 
and statistics, you can quickly fix and tune queries to get applications operational again. 
DEA is designed for A/B testing, so you can test the impact of a single change to your database.
 So DEA is ideal for optimizing your databases before doing an upgrade.

