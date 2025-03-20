# DATA-ANALYSIS-WITH-COMPLEX-QUERIES

COMPANY: CODTECH IT SOLUTION

NAME: PAYAL SANJAY KHADE

INTERN ID: CT08WBX

DOMAIN: SQL

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

This SQL script demonstrates various types of JOIN operations between two tables: EMPLOYEE and DEPARTMENT.

Creating Tables and Inserting Data: • EMPLOYEE Table: The EMPLOYEE table has columns for empId, name, and dept_id. o Five employee records are inserted. • DEPARTMENT Table: The DEPARTMENT table has columns for dept_id and dept_name. o Five department records are inserted. SELECT Queries: • INNER JOIN: This query selects employees and their respective department names by matching dept_id in both tables. Only employees who have a matching department are included in the result. • LEFT JOIN: This query selects all employees and their respective department names. If an employee does not have a corresponding department (NULL dept_id), the result will still include the employee with a NULL department name. • RIGHT JOIN: This query selects all departments and their respective employees. If a department does not have any employees, the result will still include the department with a NULL employee name. • FULL OUTER JOIN: This query selects all employees and all departments. If an employee does not belong to any department, their dept_name will be NULL, and if a department does not have any employees, the employee information will be NULL. Summary of JOIN Types: • INNER JOIN: Returns only matching rows from both tables. • LEFT JOIN: Returns all rows from the left table (EMPLOYEE) and matching rows from the right table (DEPARTMENT). • RIGHT JOIN: Returns all rows from the right table (DEPARTMENT) and matching rows from the left table (EMPLOYEE). • FULL OUTER JOIN: Returns all rows when there is a match in one of the tables, with NULLs where there is no match. This script helps demonstrate the different types of joins and how they affect the output when combining data from two related tables.

OUTPUT:
![Image](https://github.com/user-attachments/assets/4f8bb47d-630e-4eeb-a76f-35693661541e)
![Image](https://github.com/user-attachments/assets/0f15cd28-0f2b-41a9-84c4-7977ee5cf3bf)
![Image](https://github.com/user-attachments/assets/05347083-12ef-42cf-858a-85419d96a717)
![Image](https://github.com/user-attachments/assets/a2f0dcdd-8b73-4c16-b8fb-791325b1f663)
![Image](https://github.com/user-attachments/assets/98987040-0351-46ef-982f-02370b1d33b4)
![Image](https://github.com/user-attachments/assets/697bab99-a067-4561-adf5-897725e9bef4)
![Image](https://github.com/user-attachments/assets/5026b035-d980-4069-bb0f-5e62caaef029)
![Image](https://github.com/user-attachments/assets/e3a0f733-2eeb-454e-a9c5-4d882f5c0345)
