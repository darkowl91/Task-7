Task-7
======

Hibernate Employees

Create tables for entities with relations of entities as follows:
COUNTRY 1 - * CITY
CITY 1 - * ADDRESS
COMPANY * - * EMPLOYEE
COMPANY * - * ADDRESS
EMPLOYEE 1 - 1 ADDRESS

Create page employeeList.jsp with list of first 100 employees with employees information.
Name(First Name + LastName), Address(String) of employee,  Offices (company name, city, country, address, count of employees for given company office, position of given employee in office) where employee works. 
Take into account possible performance problems and choose preferable optimization approaches to reduce quantity of queries. 

Use Oracle database. Fill in every table with about 10000 records. Do not use the database VIEW. Use XML mappings approach.
