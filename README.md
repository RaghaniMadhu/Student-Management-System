# Student-Management-System

This is a student management system which does CRUD operations in Python with Oracle as database
username : system
password : abc123
Also, this project shows splash in which a quote of the day is scraped of that particular day from https://www.brainyquote.com/quote_of_the_day.html
Also, on the splash location and weather is displayed.
Along with this an additional feature it shows a graph of marks of students using matplotlib of python. 

To run the project:
Install bs4, cx_Oracle, lxml libraries by pip install on cmd prompt.

Run this query on command line of oracle database:
 create table student(rno int primary key, name varchar(20) not null, marks int not null);
