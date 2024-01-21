# EDARelatedRepo

Introduction:

In this Python project, ABC company details contains the details of employees like age,height,weight,position,etc.First of we thoroughly analyze the with EDA(Exploratory Data Analysis) method.After that we get a clear idea about the dataset.
The key objectives included:
<ul>
<li>First of all Imported essential modules: NumPy, Pandas, Seaborn, Matplotlib.</li>
<li>Then check any missing data or reaarrange the data in the dataSet.</li>
<li>In this project we changed the data in the column "Height' with random intergers between 150 - 180 .</li>
</ul>

After that we do the following functions,

<ul>
<li>head():This method is used to show the first 5 rows only.</li>
<li>tail():This method is used to show the last 5 rows only.</li>
<li>info():This method is used to get the information about the table.</li>
<li>describe():This method returns description of the data in the DataFrame.</li>
<li>isnull():This method method returns a DataFrame object where all the values are replaced with a Boolean value True for NULL values, and otherwise False.</li>
<li>notnull():This method DataFrame of Boolean values where False indicates the presence of NaN (Not a Number) values in the specified DataFrame.</li>
<li>duplicated():This method helps in analyzing duplicate values only. It returns a boolean series which is True only for Unique elements.</li>
<li>columns:This is an attribute that provides access to the column labels of a data frame.</li>
<li>value_counts():This function return a Series containing counts of unique values.</li>
<li>unique():This method is used to know all type of unique values in the columns.</li>
<li>nunique():This method returns the number of unique values for each column.</li>
</ul>


<h5>In this ABC company Details consists of 458 rows and 9 columns.Each columns describes below,</h5>
<ul>
<li>Name : It describes the name of each employees</li>
<li>Team : It describes where under employees plays</li>
<li>Number : It describes the number assigned to each employees</li>
<li>Position : It describes the position assigned to each employees</li>
<li>Age : It describes the age of each employees</li>
<li>Height : It describes the height of each employees</li>
<li>Weight : It describes the weight of each employees</li>
<li>College : It describes the College of each employees belongs to</li>
<li>Salary : It describes the Salary given to each employees</li>
</ul>


We get data stories are listed below,
<ol>
<li>In the ABC company details we can find Team "New Orleans Pelicans" has highest percentage of employees belongs to.Other remaining teams having almost same percentage.We done this analysis with 30 teams, in ABC company details.</li>
  <li>In the position analysis, SG has the highest count with 102 employees, PG has 92 employees, SF has 85 employees,PF has 100 employees and C with 79 employees.
<ul>
<li>Position SG : 102 Employees</li>
<li>Position PF : 100 Employees</li>
<li>Position PG : 92 Employees</li>
<li>Position SF : 85 Employees</li>
<li>Position C : 79 Employees</li>
</ul>
</li>
<li>
Most number no of employees are under 19-25 range(ie,200 employees).Remaining range and no of employees are listed below,

<ul>
<li>26-30 range : 167 employees</li>
<li>31-35 range : 68 employees</li>
<li>36-40 range : 23 employees</li>
</ul>
In the above analysis,we can see that most of are active in teenage.When increasing the age ,the employee counts decreases.

  
</li>
  <li>
    <ul>
    <li> In this above details we can stand out a conclusion, that employees under Position 'C' have spending more salary .ie,466377332.0.</li>
    <li> In case of teams,Cleveland Cavaliers have the highest total salary among the listed teams.ie,106,988,689.</li>
    </ul>
    </li>

    
<li>
   <ul>
 <li>Here "age" to "age" shows a positive correlation.</li>
 <li>"Age" to "Salary" indicates a positive but relatively weak relationship.</li>
 <li>"Salary" to "Age" indicates a symmetric nature of correlation.</li>
 <li>Here "Salary" to "Salary" shows a positive correlation.</li>
   </ul>
  
</li>
  
</ol>

Conclusion :-

The analysis provided valuable insights into various aspects including team distributions, salary expenditures across different positions, demographics concerning employee age, and correlations between age and salary within the ABC company. These findings significantly contribute to understanding the internal dynamics and resource allocation of the organization
