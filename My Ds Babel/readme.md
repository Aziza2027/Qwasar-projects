
## Technical specifications


### Part I SQL to CSV.
We will start with the SQL format to CSV

Your function will receives a connection (an sqlite3 object from import sqlite3 which will be already connected), table_name.
Your function will transform the content of table_name to CSV format and return it. (Columns separated by comma and rows separated by \n)

### Part II CSV to SQL
Your function will transform the content to SQL format by creating and the table_name and adding each rows to it.

### Part III
a) You will use your function in order to convert the list of all volcanos from CSV to SQL.

b) You will use your function in order to convert the list of all fault lines from SQL to CSV.
Data are inside the table named: fault_lines.

Write a class with two classmethod which convert a format to another. (Part I and Part II)

You are free on the implementation on how to connect to the database and which arguments to send to your functions.

Your code will be here to show to your reviewer your implementation, but we are looking for the 2 results files. ;-)
Your submit files will be: all_fault_lines.csv and list_volcanos.db (table volcanos).
