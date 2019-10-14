Csv to SQL database spript


1. I have taken a test dataset with 65k+ Records.

2. I sliced 50k records AS per the requirement.

3. Took 5 columns Series_reference,Period,Data_value,STATUS,Subject.

4. I have assumed you have already Ceated a DB named 'csv_sql' and table name 'testcsv (MYSQL WORKBENCH).

5. Create a connection with the DB throught pysql.

6. Create a cursor for the connection to execute SQL staements.

7. Insert rows from csv to database

8. Close the cursor.

9. Close the Connection.

10. Print success message and time for execution.