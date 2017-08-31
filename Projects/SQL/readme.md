### SQL Library Database
***

#### Objective
As a final project for my SQL course I was assigned to create a library management system. The project required the build of a database with a specified relational flow chart

#### Steps Taken
The first step I took was to look at the relationships of the flow chart and evaluate which tables would hold mostly their own data and which ones would contain more relationships to other tables. This assisted me in the creation of the database tables. I then created the records and populated all of the tables in the database.

Part of the project was to answer a set of questions by using SQL queries and inner joins. The results of these queries were then made accessible by writing them into a stored procedure.

I have uploaded stored procedures to both [build/populate the database](/Projects/SQL/SP_lib_system_build.sql) and [run queries](/Projects/SQL/Lib%20Project%20SP.sql)

#### The Result

I was able to get all queries to work successfully. Something that I really took away from this project is the ability to attain the same desired results through queries with different implementation. This is why I left a second implementation of one query commented out in the stored procedure. The query that does execute is a shorter and cleaner implementation, however it may not have been successful if the database were set up slightly different. This database was set up to mimic what could function as a real life application for a public library system, but for this project and the sake of simplicity some aspects were omitted or simplified like in the case of book checkout. Because of this, it is important when organizing and building a database to fully understand the intended needs and uses for the data and what kinds of queries will be made. A version of this database for actual use by entities would be slightly more complex and therefore require a more complex implementation of some queries. Along the same lines, configuring the relations of a database one way versus another might render a query to be less or more complicated to implement.

[Return to portfolio](https://github.com/zfregin/portfolio)
