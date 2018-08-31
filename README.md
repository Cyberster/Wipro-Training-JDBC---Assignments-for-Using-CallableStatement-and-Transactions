Wipro TalentNext PBL

Topics Covered: CallableStatement


No. 	Hands-on Assignment 	Topics Covered 	Status

1 	

Create a stored procedure that calculates net salary of all the employees whose records are stored in table "emp".
The criteria for calculating net salary is as follows :
Gross salary = sal + comm.
Net Salary = gross salary - IT
If the employee's commission is null then IT is calculated as
IT =  10% of gross salary
else if the employees commission is less than 500, then IT is calculated as
IT =  15% of gross salary
else
IT = 20% of gross salary.
Develop a jdbc program that invokes this stored procedure by passing the empno. and in return gets the net salary of each employee. Display on screen the empno., ename and net salary of all the employees.

	CallableStatement 	