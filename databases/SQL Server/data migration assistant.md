supports versions 2005 and higher

Using the assistant, you connect to the instance and select the database you plan to upgrade. You tell the assistant the target version of SQL Server and it will analyze the size and schema of the database. The assistant will also make recommendations for your upgrade. After the analysis, DMA provides a compatibility report, which highlights breaking changes, behavioral changes, and deprecated features, so these problems can be fixed.

DMA also makes recommendations for how the database uses performance, storage, and security features in the target version. These results can be exported to a CSV or JSON file for future reference. This situation is ideal when you have a large number of databases for upgrade and need a concise list of tasks to prevent application failure after upgrading. You then use DMA to upgrade your database and logins to the target server.

Most usefully, DMA highlights deprecated features in older databases so you can see the code that will break, before you begin the upgrade. DMA also suggests features that will boost security and performance, and the results can be exported
