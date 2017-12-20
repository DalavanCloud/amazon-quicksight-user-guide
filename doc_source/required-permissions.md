# Required Permissions for Database Credentials<a name="required-permissions"></a>

You must provide a user name and password for a database in order to connect to it\. The user account identified by these credentials must have `SELECT` permissions on some system tables in order to allow Amazon QuickSight to do things like discover table schemas and estimate table size\. 

The following table identifies the tables that the user account must have `SELECT` permissions on, depending on the type of database you are connecting to\. These requirements apply for all database instances you connect to, regardless of their environment \(whether they are on\-premise, in Amazon RDS, in Amazon EC2, etc\.\)\.


****  

| Instance Type | Tables | 
| --- | --- | 
|  **Amazon Aurora**   |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/quicksight/latest/user/required-permissions.html)  | 
|  **Amazon Redshift**   |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/quicksight/latest/user/required-permissions.html)  | 
|  **MariaDB**   |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/quicksight/latest/user/required-permissions.html)  | 
|  **Microsoft SQL Server**   |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/quicksight/latest/user/required-permissions.html)  | 
|  **MySQL**   |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/quicksight/latest/user/required-permissions.html)  | 
|  **PostgreSQL**   |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/quicksight/latest/user/required-permissions.html)  | 

**Note**  
 If you are using MySQL or PostreSQL, verify that you are connecting from an allowed host or IP address\. See [Database Configuration Requirements for Self\-Administered Instances](configure-access.md#database-configuration-requirements) for more detail\. 