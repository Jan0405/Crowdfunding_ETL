# Crowdfunding_ETL
## Project Description
Worked with a partner to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After transforming the data, created four CSV files and use the CSV file data to create an ERD and a table schema. Finally, uploaded the CSV file data into a Postgres database.

## Approach 
----------------------------
+ Used crowdfunding data from the Excel file, which contains the campaign contribution information.
+ Loaded Excel file into Pandas DataFrame.
_____________________________
![image](https://user-images.githubusercontent.com/120051602/227099675-05796377-3cbf-4f36-b710-287b4ce91bc8.png)

+ Created few columns to organize the data neatly ex. category and subcategory columns
______________________________
![image](https://user-images.githubusercontent.com/120051602/227099749-b231596f-40bf-47e2-8728-b27c86afb69c.png)

+ Created DataFrame from those new columns to categorize the data
____________________________
![image](https://user-images.githubusercontent.com/120051602/227099834-6030f96b-8ef4-4543-9733-012b6507f5f1.png)

+ Changed the data types of few columns where it was required
+ Merged the DataFrames
____________________________
![image](https://user-images.githubusercontent.com/120051602/227100003-5bd69d75-33cb-485f-973c-8285f024552d.png)

+ Used regex to create the DataFrame
_____________________________
![image](https://user-images.githubusercontent.com/120051602/227100154-3636492c-b587-4089-976a-2371eee915d1.png)
![image](https://user-images.githubusercontent.com/120051602/227100213-82bf1872-99c4-4c6d-8853-785fa8e526ab.png)
![image](https://user-images.githubusercontent.com/120051602/227100285-971550b5-49c7-46d9-8b24-f14b851e8c3c.png)
![image](https://user-images.githubusercontent.com/120051602/227100394-4b991973-718a-46ca-a10e-bd8907c05f78.png)

+ Dropped unwanted columns and created new clean DataFrame
+ Exported the clean DataFrame to the csv file
______________________________
![image](https://user-images.githubusercontent.com/120051602/227100522-80a7be1f-f713-4e58-95bd-436559214657.png)
![image](https://user-images.githubusercontent.com/120051602/227100681-5b65ef4a-618c-4ba0-9a6f-7340eaf78bd8.png)
![image](https://user-images.githubusercontent.com/120051602/227100765-11abcb3a-e914-400b-9d5e-cf1bdf56ee73.png)

+ Finally, loaded CSV files into the Postgres Database.
_______________________________
<img width="796" alt="ERD_campaign" src="https://user-images.githubusercontent.com/120051602/227102211-439547d0-c901-4b42-b2c8-32e15ac7ac29.png">


