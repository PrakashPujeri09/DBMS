# DBMS
show  databases;
use newdatabase;

CREATE TABLE STUDENT(
stdid int(5),stdname varchar(20),dob date,doj date ,fee int(10),gender char);

desc STUDENT;

insert into STUDENT (stdid,stdname,dob,doj,fee,gender)values(1,"prakash",'2001-01-01','2001-01-01',11800,"M");
select * from  STUDENT;

insert into STUDENT (stdid,stdname,dob,doj,fee,gender)values(2,"prutvi",'2003-01-01','2002-01-01',11800,"M");

alter  table STUDENT add ph_no int(10); 

alter  table STUDENT rename column ph_no to std_no; 
select * from  STUDENT;

alter  table STUDENT drop column gender;
alter table STUDENT rename to student_info;

select * from  STUDENT;
desc STUDENT;
select * from  STUDENT;
