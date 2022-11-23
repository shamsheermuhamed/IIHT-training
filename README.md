# IIHT-training

Ques.1. Write an SQL query to fetch the EmpId and FullName of all the employees working under the Manager with id – ‘986’.
Select empid,fullname from employeedetails where managerid=986;

Ques.2. Write an SQL query to fetch the different projects available from the EmployeeSalary table.
Select distinct project from employeesalary;

Ques.3. Write an SQL query to fetch the count of employees working in project ‘P1’.
Select count(*) from employeesalary where project=’P1’;

Ques.4. Write an SQL query to find the maximum, minimum, and average salary of the employees.
Select max(salary),min(salary), avg(salary) from employeesalary;

Ques.5. Write an SQL query to find the employee id whose salary lies in the range of 9000 and 15000.
Select empid from employeesalary where salary between 9000 and 15000;

Ques.6. Write an SQL query to fetch those employees who live in Toronto and work under the manager with ManagerId – 321.
Select * from employeedetails where city=’Toronto’ and managerid=321;

Ques.7. Write an SQL query to fetch all the employees who either live in California or work under a manager with ManagerId – 321.
Select * from employeedetails where city=’ California’ or managerid=321;

Ques.8. Write an SQL query to fetch all those employees who work on Projects other than P1.
Select * from employeedetails where project !=’P1’;

Ques.9. Write an SQL query to display the total salary of each employee adding the Salary with Variable value.
Select salary+variable as totalsalary from employeesalary;

Ques.10. Write an SQL query to fetch the employees whose name begins with any two characters, followed by a text “hn” and ends with any sequence of characters.
Select * from employeedetails where fullname like ‘__hn%’;

Ques.11. Write an SQL query to fetch all the EmpIds which are present in either of the tables – ‘EmployeeDetails’ and ‘EmployeeSalary’.

Ques.12. Write an SQL query to fetch common records between two tables.

Ques.13. Write an SQL query to fetch records that are present in one table but not in another table.

Ques.14. Write an SQL query to fetch the EmpIds that are present in both the tables –   ‘EmployeeDetails’ and ‘EmployeeSalary.


Ques.15. Write an SQL query to fetch the EmpIds that are present in EmployeeDetails but not in EmployeeSalary.

Ques.16. Write an SQL query to fetch the employee’s full names and replace the space with ‘-’.

Ques.17. Write an SQL query to fetch the position of a given character(s) in a field.

Ques.18. Write an SQL query to display both the EmpId and ManagerId together.


Ques.19. Write a query to fetch only the first name(string before space) from the FullName column of the EmployeeDetails table.



Ques.20. Write an SQL query to uppercase the name of the employee and lowercase the city values.



Ques.21. Write an SQL query to find the count of the total occurrences of a particular character – ‘n’ in the FullName field.



Ques.22. Write an SQL query to update the employee names by removing leading and trailing spaces.


Ques.23. Fetch all the employees who are not working on any project.



Ques.24. Write an SQL query to fetch employee names having a salary greater than or equal to 5000 and less than or equal to 10000.



Ques.25. Write an SQL query to find the current date-time.




Ques.26. Write an SQL query to fetch all the Employee details from the EmployeeDetails table who joined in the Year 2020.



Ques.27. Write an SQL query to fetch all employee records from the EmployeeDetails table who have a salary record in the EmployeeSalary table.


Ques.28. Write an SQL query to fetch the project-wise count of employees sorted by project’s count in descending order.

Ques.29. Write a query to fetch employee names and salary records. Display the employee details even if the salary record is not present for the employee.


Ques. 30. Write an SQL query to fetch all the Employees who are also managers from the EmployeeDetails table.
select * from employeedetails where empid in (select managerid from employeedetails);

