# EXP 02 - CREATE A SQL PROGRAM TO FETCH THE NO OF WORKS FOR EACH DEPARTMENT.

## AIM:

 To fetch the given column and arrange the values in descending order using SQL.
 
## ALGORITHM:

1) Create a sample table in SQL using CREATE TABLE syntax
2) Insert all the values and Titles respectively using INSERT INTO syntax
3) Now check whether all the rows are affected or not by fetching the table
4) After checking, now use SELECT for choosing the column name that we meant to sort and use FROM to choose the table
5) Then use ORDER BY syntax to sort the rows in ascending or descending order using desc, asc.
6) After compiling and running the program, the results will be displayed.

## PROGRAM:

```java
create table Employee(
  Sno int,
  Department varchar(50),
  No_of_workers int
);
insert into Employee (Sno,Department,No_of_workers)
values (1,'Development',15);
insert into Employee (Sno,Department,No_of_workers)
values (2,'Frontend Dv',10);
insert into Employee (Sno,Department,No_of_workers)
values (3,'Backend DV',7);
insert into Employee (Sno,Department,No_of_workers)
values (4,'Finance MM',8);
insert into Employee (Sno,Department,No_of_workers)
values (5,'Designer',12);
insert into Employee (Sno,Department,No_of_workers)
values (6,'Marketing',25);
insert into Employee (Sno,Department,No_of_workers)
values (7,'Chief heads',4);
insert into Employee (Sno,Department,No_of_workers)
values (8,'Law persuit',3);

select Department, No_of_workers from Employee
order by Department,No_of_workers desc;

```
## OUTPUT:

<img width="406" alt="image" src="https://github.com/Monisha-11/EXP-02---NO_OF_WORKERS-IN-DEPT/assets/93427240/43ca7519-cf11-4740-90ea-9f4e90f83cc9">


## RESULT:
Thus we have successfully arranged the column values in descending order using the above-given code.
