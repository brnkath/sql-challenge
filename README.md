# sql-challenge

SQL challenge to research and organize employees working for a fictional company in the 1980's and 1990's.

Contributor: Brian Kath

Repository Structure - 

 - Main folder
	 - README.md file

 - Sub-folders
	- EmployeeSQL
		 - data
			- departments.csv
			- dept_emp.csv
			- dept_manager.csv
			- employees.csv
			- salaries.csv
			- titles.csv
		- data_analysis
			- employees_analysis.sql
		- data_engineering
			- table_schema.sql
		- data_modeling
			- ERD.png
			- ERD_w_text.png

Overview - 

For this project, I used pgAdmin to construct tables a run queries to analyze employee data from 6 csv files for a fictional company. I first used quickdatabasediagrams.com to create an ERD for the table structure I would be using in pgAdmin. I then exported the table schema and imported it into pgAdmin to construct the tables. I then imported the data from the 6 csv files into the tables created. Finally, I performed an analaysis using apporopriate queries to complete the following tasks.

List the employee number, last name, first name, sex, and salary of each employee.

List the first name, last name, and hire date for the employees who were hired in 1986.

List the manager of each department along with their department number, department name, employee number, last name, and first name.

List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

List each employee in the Sales department, including their employee number, last name, and first name.

List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).
