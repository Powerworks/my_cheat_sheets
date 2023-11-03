Azure SQL Managed Instance is a fully functional SQL Server instance that is almost 100% compatible with your on-premises ecosystem including features like SQL Agent, access to tempdb, cross-database query and common language runtime (CLR). The service uses the same infrastructure as Azure SQL Database and includes all the benefits of the PaaS service such as automatic backups, automatic patching, and built-in high availability, just to name a few.

 Managed Instance provides an entire SQL Server instance, allowing up to 100 databases, as well as providing access to the system databases. Managed Instance provides other features that are not available in Azure SQL Database, including cross-database queries, common language runtime (CLR) and along with the msdb system database, it allows the use of SQL Agent.
 
There are two service tiers available when creating an Azure SQL Managed Instance, and they are the same as Azure SQL Database vCore model (managed instance is purchased using the vCore model), Business Critical and General Purpose. There are minimal functionality differences between the two tiers—the main two are that Business Critical includes In-Memory OLTP and offers a readable secondary, neither of which is available with the General Purpose tier. Both tiers offer the same levels of availability and allow for independent configuration of storage and compute.

RESTORING A DB

Restoring a database to an Azure SQL Managed Instance is also similar to the 
process with Azure SQL Database. You can use:

Azure portal

PowerShell

Azure CLI

However, there are some limitations when restoring. In order to restore from one 
instance to another, both instances must reside within the same Azure subscription 
as well as the same Azure region. You also cannot restore the entire managed instance, 
only individual databases within the Managed Instance itself.
