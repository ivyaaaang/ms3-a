# ms3

Jr. Coding Challenge


## SUMMARY
-This Java Application will
1. consume a CSV file 
2. verify every rows in the file 
  - if it contains the right number of data elements, the data will be inserted in the database, test.db 
  - if not, the data will be inserted in a csv file, bad.csv 
3. display and create a log file that has 
  - no. of recieved data 
  - no. of successful data inserted in the database, test.db 
  - no. of failed data inserted in the csv file, bad.csv
  
## OVERVIEW
- I decided to use netbeans ide to create this java project.
- i used jframe form to create the user interface of the project
- i used JFileChooser to open a file manager and select a file, after selecting the file it will get the file's absolute path
- After getting the path of the csv file, I used a bufferedreader to read the file.
- The bufferedreader will read every line/rows of the file, if the record in every row match the column count the data will be inserted in the sqlite database, if not the data will be inserted in a csv file.
- this java project will also display the no. of recieved data, no. of successful data inserted in the database, test.db and no. of failed data inserted in the csv file, bad.csv


## GETTING STARTED
- clone the repository
  - you can open and run the executable jar file that can be found in the ms3/dist/ms3.jar or
  - you can open command prompt and enter "java -jar <actual\path\of\the\file\file_name.jar"
  - if you have netbeans ide, you can import the project and run through the netbeans ide
