Q1. How do you load a CSV file into a Pandas DataFrame?

Ans: It is done using a pandas.read_csv () method. We have to import pandas library to use this method.

Q2.How do you check the data type of a column in a Pandas DataFrame?

Ans: We can use  below syntax to check the data type of a particular column in Pandas DataFrame:
Syntax : df['DataFrame Column'].dtypes

Q3. How do you select rows from a Pandas DataFrame based on a condition?

Ans: Selecting rows based on particular column value using '>', '=', '=', '<=', '!=' operator.

Q4. How do you rename columns in a Pandas DataFrame?

Ans: 1: Using Dataframe.rename (). This method is a way to rename the required columns in Pandas. It allows us to specify the columns’ names to be changed in the form of a dictionary with the keys and values as the current and new names of the respective columns.

Q5. How do you drop columns in a Pandas DataFrame?

Ans:Drop Columns from a Dataframe using drop() method.
Drop Columns from a Dataframe using iloc[] and drop()

Q6. How do you find the unique values in a column of a Pandas DataFrame?

Ans: Using unique() method
pandas.DataFrame().unique() method is used when we deal with a single column of a DataFrame and returns all unique elements of a column. The method returns a DataFrame containing the unique elements of a column, along with their corresponding index labels.

Q7. How do you find the number of missing values in each column of a Pandas DataFrame?

Ans: To get the count of missing values in each column of a dataframe, you can use the pandas isnull() and sum() functions together. The following is the syntax:

# count of missing values in each column
df.isnull().sum()

Q8. How do you fill missing values in a Pandas DataFrame with a specific value?

Ans: 







