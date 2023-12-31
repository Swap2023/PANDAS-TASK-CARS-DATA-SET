**# PANDAS-CARS-DATA-SET.

#CARS
Q. 1) Find all null values in the data. If there is any null value in that column then fill that value with mean of that column.
Q.2) Check what are the types of makes are there in our dataset, and what is the count(occurrence) of each make in the data.
Q.3) Show all the records where origin is Asia or Europe.
Q.4) Remove all the records where weight is above 4000.
Q.5) Increase all the values of MPG_City by 3.
The commands that we used in this project :

* import pandas as pd -- To import Pandas library
* pd.read_csv - To import the CSV file in Jupyter notebook
* head() - It shows the first N rows in the data (by default, N=5)
* shape - It shows the total no. of rows and no. of columns of the dataframe
* df.isnull( ).sum( ) - It detects the missing values from each column of the dataframe.
* fillna() - To fill the null values of a column with some particular value
* value_counts - In a column, it shows all the unique values with their count. It can be applied to a single column only.
* isin() - To show all records including particular elements
* apply() - To apply a function along any axis of DF
**
