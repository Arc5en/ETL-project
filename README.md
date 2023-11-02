# ETL-project

From the two Excel files, I created 4 different data frames in my jupyter notebook using Pandas (ETL_Mini_Project_Starter_Code.ipynb). Each of these became the 4 CSV files in the Resources folder.
I was able to successfully extract the data from the excel files and transform them using Pandas into CSV files.

Using these CSV files, I created a table schema in PostgreSQL to upload them into a database using crowdfunding_db_schema.sql. This setup allowed me to import the data using the CSV files I created earlier.
Once I uploaded the CSV files, I successfully loaded my data in the CSV files into PostgreSQL.
