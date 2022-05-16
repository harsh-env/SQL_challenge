# SQL_challenge
Bootcamp sql challenge HW
## 1. Data Modeling 
QuickDBD was used to visulize the relationship of data provided in 6 separate csv files for developing a SQL database for employees in a major corporation hired during the 1980's to 1990's. 
![](https://github.com/harsh-env/SQL_challenge/blob/main/Employee_sql/QuickDBD-export%20(3).png)
## 2. Data Engineering
Table Schema for each of the 6 csv's were generated by specifying data types, Primary & Foreign Keys and other constraints om Postgresql. The Schema is illustrated in EMPLOYEES_DB2_Schema.sql file
## 3. Data Analysis
The sql file Query_data_analysis_Emply_DB.spl illustrates the queries used to generated the necessary outputs

1. Listing the employee number, last name, first name, gender, and salary.
![](https://github.com/harsh-env/SQL_challenge/blob/main/Employee_sql/Screenshot_ans_key/Data_Analysis_Q1.JPG)

2. List first name, last name, and hire date for employees who were hired in 1986
![](https://github.com/harsh-env/SQL_challenge/blob/main/Employee_sql/Screenshot_ans_key/Data_Analysis_Q2.JPG)

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
![](https://github.com/harsh-env/SQL_challenge/blob/main/Employee_sql/Screenshot_ans_key/Data_Analysis_Q3.JPG)

4. List the department of each employee with the following information: employee number, last name, first name, and department name.
![](https://github.com/harsh-env/SQL_challenge/blob/main/Employee_sql/Screenshot_ans_key/Data_Analysis_Q4.JPG)

5. List first name, last name, and sex for employees whose: first name is "Hercules" and last names begin with "B."
![](https://github.com/harsh-env/SQL_challenge/blob/main/Employee_sql/Screenshot_ans_key/Data_Analysis_Q5.JPG)

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.
![](https://github.com/harsh-env/SQL_challenge/blob/main/Employee_sql/Screenshot_ans_key/Data_Analysis_Q6.JPG)

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
![](https://github.com/harsh-env/SQL_challenge/blob/main/Employee_sql/Screenshot_ans_key/Data_Analysis_Q7.JPG)

8. List the frequency count of employee last names (i.e., how many employees share each last name) in descending order.
![](https://github.com/harsh-env/SQL_challenge/blob/main/Employee_sql/Screenshot_ans_key/Data_Analysis_Q8.JPG)
