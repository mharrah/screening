## SQL Challenge

### Get as far as you can with these three exercises

1.  Setup a SQLTest database on your SQL instance and setup 3 tables with data in them in this instance using one of these two methods:
    - Execute the DACPAC into your local dev SQL instance to create the SQLTest database *note: you can run it repeatedly but it will recreate the database each time*
	- Create the SQLTest database, then go to the "Tables" folder and execute each SQL to create the tables. Then go to the "PostDeploy" folder to insert the test data
    - **Include a screenshot of the completed database**
	
2.  Write a SQL script to find the package and environment table combination with the most recent **date** and update the LastChange table's DateComplete using SQL:
    - ![LastChange Table Picture](desiredtable.png)
    - **Include the script if completed**

3.  Build the DACPAC into a *.dacpac file and use command-line sqlpackage to use the SQLTest.publish.xml file to publish to your local database
    - **Include the *.dacpac file and the full command used in your cmd publish**
	
4.  Normalize the database
    - **OPTION 1: Update the dacpac and send the dacpac back normalized**
	- **OPTION 2: Update/add files to the tables and postdeploy folders and return the files in those folders**