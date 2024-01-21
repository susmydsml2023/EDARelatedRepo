# EDARelatedRepo

Introduction:

In this Python project, ABC company details contains the details of employees like age,height,weight,position,etc.First of we thoroughly analyze the with EDA(Exploratory Data Analysis) method.After that we get a clear idea about the dataset.
The key objectives included:
-First of all Imported essential modules: NumPy, Pandas, Seaborn, Matplotlib.
-Then check any missing data or reaarrange the data in the dataSet.
-In this project we changed the data in the column "Height' with random intergers between 150 - 180 .


After that we do the following functions,

-head():This method is used to show the first 5 rows only.
-tail():This method is used to show the last 5 rows only.
-info():This method is used to get the information about the table.
-describe():This method returns description of the data in the DataFrame.
-isnull():This method method returns a DataFrame object where all the values are replaced with a Boolean value True for NULL values, and otherwise False.
-notnull():This method DataFrame of Boolean values where False indicates the presence of NaN (Not a Number) values in the specified DataFrame.
-duplicated():This method helps in analyzing duplicate values only. It returns a boolean series which is True only for Unique elements.
-columns:This is an attribute that provides access to the column labels of a data frame.
-value_counts():This function return a Series containing counts of unique values.
-unique():This method is used to know all type of unique values in the columns.
-nunique():This method returns the number of unique values for each column.



<h5>In this ABC company Details consists of 458 rows and 9 columns.Each columns describes below,</h5>

Name : It describes the name of each employees
Team : It describes where under employees plays
Number : It describes the number assigned to each employees
Position : It describes the position assigned to each employees
Age : It describes the age of each employees
Height : It describes the height of each employees
Weight : It describes the weight of each employees
College : It describes the College of each employees belongs to
Salary : It describes the Salary given to each employees

Conclusion :-

The analysis provided valuable insights into various aspects including team distributions, salary expenditures across different positions, demographics concerning employee age, and correlations between age and salary within the ABC company. These findings significantly contribute to understanding the internal dynamics and resource allocation of the organization
