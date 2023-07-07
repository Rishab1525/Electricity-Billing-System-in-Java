# Electricity-Billing-System-in-Java
Electricity-Billing-System-in-Java
DATABASE QUERYS IN MYDQL RUN 


create database hms;
use hms;
create table login(username varchar(40),password varchar(40));
insert into login values('rishab','rishab1507');
create table customer (id varchar(30),number varchar(30),name varchar(30),gender varchar(30),country varchar(30),room_number varchar(30),status varchar(30),deposit varchar(30));

create table room(room_number varchar(20),availability varchar(20),clean_status varchar(20), price varchar(20),bed_type varchar(30));
create table employee(name varchar(30), age varchar(10),gender varchar(30),job varchar(30),salary varchar(30),phone varchar(30),aadhar int(30),email varchar(40));
create table driver(name varchar(30),age int(10),gender varchar(10), location varchar(50));


PROJECT VIEWS 

Admin Login View 
![Electricity-Billing-System-in-java](/public/1.png)

User Login view 
![Electricity-Billing-System-in-java](/public/2.png)

New Customer Add Page 
![Electricity-Billing-System-in-java](/public/3.png)

Meter Information 
![Electricity-Billing-System-in-java](/public/4.png)

Login page view 
![Electricity-Billing-System-in-java](/public/5.png)

Report View 
![Electricity-Billing-System-in-java](/public/6.png)
