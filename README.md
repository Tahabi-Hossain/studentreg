This Windows Forms application allows users to perform basic CRUD (Create, Read, Update, Delete) operations on a SQL Server database through a graphical user interface (GUI). The connected database, demo.mdf, contains a table named InfoTable.


Features
Insert: Adds a new record to the database.
Update: Modifies an existing record.
Delete: Removes a record from the database.

GUI Elements
Text Fields:

ID: Unique identifier (Primary Key).
First Name: User's first name.
Last Name: User's last name.
Age: User's age.
Buttons:

Insert (Pink): Insert new data.
Update (Green): Update selected record.
Delete (Red): Delete selected record.

Database Schema
Database: demo.mdf
Table: InfoTable
ID (int, Primary Key)
FirstName (varchar)
LastName (varchar)
Age (int)


Setup Instructions :
Open the project in Visual Studio.
Attach demo.mdf to your local SQL Server instance.
Modify the connection string if necessary.
Run the application.
Troubleshooting
Ensure SQL Server is running.
Verify the database connection string.

