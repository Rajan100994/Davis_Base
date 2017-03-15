# Davis_Base
SQL Engine implementation. Davis_Base is a hybrid of SQLite and MySQL. 

run DavisBase.java
Please use the syntax as is….

Supported sql commands and their syntax are as follows :

1) show tables;
-> gives the list of all tables

2) select * from davisbase_columns;
-> file having the column details of each file

3) select * from davisbase_tables;
-> file having the table details of each file


4) Create
create table rajan (id int primary key,name text [not null],age int,height int);

5) Insert
insert into table (id,name,age,height) rajan values (1,raj,22,71);

6)Select

select * from rajan;
select name from rajan;
select height from rajan;
select * from rajan where row_id > 1;
select * from rajan where row_id = 1;
select name from rajan where age = 22;
select name from rajan where age > 22;
select name from rajan where age < 22;

7)Update
update rajan set age = 24 where name = raj;

Delete
delete from table rajan where row_id = 3;

Drop
drop table rajan;



	Optional Feature 
1) Index Files generated for each column as .ndx files
