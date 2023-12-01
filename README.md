# SQL project

## Description
This project involves the design of database tables sourced from CSV files, incorporating expertise in data modeling and engineering. Subsequently, a strategic data analysis phase is executed to address precise research inquiries with a focus on accuracy and insightfulness.

## Technologies Used
quickdatabasediagrams (database diagraming tool)
PostgreSQL (data analysis)

## File Structure
### EmployeeSQL
- 'Employees_data_analysis.sql': example of SQL script to perform top level analysis on company demographics.
- 'Employees_schema.sql': SQL script that outlines the architecture of a relational database, featuring tables that are stored in CSV format within *data* folder.

## Instructions




Data base is designed based on the provided .csv files by completing the following steps:

 1. Data Modeling. ERD was sketched using Quick DBD tool (Employees_db_ERD.png).

 2. Data Engineering. A database and the respective tables were created (Employees_schema.sql), followed by uploading the data from .csv files to the corresponding created tables.

 3. Data Analysis. Initial steps in understanding the data was performed (Employees_data_analysis.sql), including:
    - Preparing a list of the employees info, incl. the employee number, last name, first name, sex, and salary of each employee.
    - Listing the employees (first name, last name, and hire date) who were hired in 1986 ().
    - Listing the managers of each department, displaying department number, department name, employee number, last name, and first name.
    - Preparing a list of the employees info, incl. department number, department name, employee number, last name and first name.
    - Listing all the employees whose first name is Hercules and whose last name begins with the letter B (the results includes empoyees' first name, last name, and sex).
    - Preparing a list of the employees in Sales department, including their employee number, last name, and first name.
    - Preparing a list of the employees in Sales and Development departments, including their employee number, last name and first name.
    - Grouping the employees by their last name and listing the frequency counts for each "last name group" in descending order (how many employees share each last name).


## Results