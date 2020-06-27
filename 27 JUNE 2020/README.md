# 27 june 2020

# DBMS 
 
 1.Consider the following relations:
Student (snum: integer, sname: string, major: string, level: string,age: integer)
Class (name: string, meets at: string, room: string, d: integer)
Enrolled (snum: integer, cname: string)
Faculty (fid: integer, fname: string, deptid: integer)
The meaning of these relations is straightforward; for example,
Enrolled has one record per student-class pair such that the student
is enrolled in the class. Level is a two character code with 4 different values (example: Junior: JR etc)

2.Consider the following database for a banking enterprise
BRANCH(branch-name:string,branch-city:string,assets:real)
ACCOUNT(accno:int,branch-name:string,balance:real)
DEPOSITOR(customer-name:string,accno:int)
CUSTOMER(customer-name:string,customer-street:string,city:string)
LOAN(loan-number:int,branch-name:string,loan-number-int)
BORROWER(customer-name:string,customer-street:string,city:string)

