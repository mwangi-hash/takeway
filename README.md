create table James(

 Student_id int primary key,
 First_name varchar(100),
 Last_Name varchar(100),
 age int,
 email varchar(255)
 );
 
 insert into james( Student_id,First_name,Last_Name,age,email)
 values 
 (1,'john','Doe',20,'john.doe@example.com'),
 (2,'jane','smith',22,'jane.smith@example.com'),
 (3,'michael','brown',19,'michael.brown@example.com')
 ;


Alter table james ADD Enrolment_date varchar(255)
 ;
ALTER  table james modify Enrolment_date date; 
alter table james modify email varchar(300);
