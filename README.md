# ASD-S5.D
SQL
   
create table student(sno varchar(10),name varchar(10),marks int(50),dept varchar(15));
alter table student
	add(age int(23));
alter table student
	modify(dept varchar(20));
alter table student
	drop column marks;
rename student to students;
delete from students;
drop table students;
