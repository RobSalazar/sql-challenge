# SQL Homework - Employee Database: A Mystery in Two Parts

<p align="center">
  <img src="https://github.com/RobSalazar/sql-challenge/blob/main/sql.png" />
</p>

## Background

It is a beautiful spring day, and it is two weeks since you have been hired as a new data engineer at Pewlett Hackard. Your first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

## Instructions

#### Data Modeling
![employee_db_ERD.png](https://github.com/RobSalazar/sql-challenge/blob/main/images/employee_db_ERD.png)
[Click here to make your own ERD!](http://www.quickdatabasediagrams.com)

#### Data Engineering

* Use the information you have to create a table [schema](https://github.com/RobSalazar/sql-challenge/blob/main/EmployeeSQL/tables_schema.sql) for each of the six CSV files. Remember to specify data types, primary keys, foreign keys, and other constraints.

#### [Data Analysis](https://github.com/RobSalazar/sql-challenge/blob/main/EmployeeSQL/data_analysis.sql)

Once you have a complete database, do the following:

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

2. List first name, last name, and hire date for employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

## Bonus 

As you examine the data, you are overcome with a creeping suspicion that the dataset is fake. You surmise that your boss handed you spurious data in order to test the data engineering skills of a new employee. To confirm your hunch, you decide to take the following steps to generate a visualization of the data, with which you will confront your boss:

Create a histogram to visualize the most common salary ranges for employees.
![employee_salary_histogram.PNG](https://github.com/RobSalazar/sql-challenge/blob/main/images/employee_salary_histogram.PNG)

Create a bar chart of average salary by title.
![employee_salary_barchart.PNG](https://github.com/RobSalazar/sql-challenge/blob/main/images/employee_salary_barchart.PNG)

## Epilogue

Evidence in hand, you march into your boss's office and present the visualization. With a sly grin, your boss thanks you for your work. On your way out of the office, you hear the words, "Search your ID number." You look down at your badge to see that your employee ID number is 499942.

![epilogue.PNG](https://github.com/RobSalazar/sql-challenge/blob/main/images/epilogue.PNG)
