# Easy Realtor

## We created this database to manage the needs of a potential real estate company
All neccesary files and installation instructions are under the install folder

### Populating the database
- Open milestone3dump.sql in MySQL. You should see SQL code that will populate the entire Easy Realtor database. Run it in your local connection. It might take a few seconds. But you should be able to see these tables after refreshing.
- ![image](https://user-images.githubusercontent.com/63078191/184553243-74742bda-9016-418c-9d4b-11bd430ec9cf.png)
- Tables should be populated and you can double check by select * from each table. Tables are populated using mock data from mockaroo

### Running the queryRunner
- Under install folder, you should see a zip file called queryrunner.zip
- Unzip the file, you should get a folder with a few java files and a jar file
- You can either run the jar file from terminal, or you can simply double click on it and bring up the GUI.
- If the jar file doesn't work, you can always run the main QueryRunner class.
- We will double click the jar file and open the GUI version
- ![image](https://user-images.githubusercontent.com/63078191/184553422-44917b5a-af54-41f2-a660-ac1e331a7ed7.png)
- Here, you enter your local database's login information and the database name is ‘mm_cpsc502102team03’
- When accessing the app through console version. You will still input the same credentials but with this interface.
- ![image](https://user-images.githubusercontent.com/63078191/184553470-90b3b1ce-be35-4e8f-a9e2-424e4b0fa300.png)
- In the console version, all queries' descriptions are printed out to select easier.
- We have 14 queries preloaded. Whenever you select a new query, its query description and input type is printed in the output box.
- I will list the input ranges for queries that require inputs below:
  - Query 1: Input states: IA, WA, MT, OR, SD, ID, ND
  - Query 2: Deal status open or closed
  - Query 3: Employee ID 1-500, Date in SQL date format 'YYYY-MM-DD'
  - Query 6: Property ID 101-850
  - Query 10: Number of listed properties
  - Query 13: Insert into price table. Price ID 1-773, when inserting   new row, start at 774. Property ID 101-850. Price can be whatever positive price. Deal is from 1-755, so deal id start at 756 if inserting new row.
  - Query 14: Update employee wage. Base salary any dollar amount, commission can be any percent in decimal form. And employee id 1-500
And you are done! You have populated Easy Realtor's entire database and the application.
