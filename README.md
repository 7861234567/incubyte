
#importing the module 
import sqites 
#creating an connection 
conn sqlite3.connect("incubyte.db) # db - database 
# Cursor object cursor = conn.cursor) 
#code to create a databse table 
create table_sql= 
CREATE TABLE name stng 
Name VARCHAR(20) 
Cust 
Open_Dt NT 
Consul LDt INT, 
VAC_ID VARCHAR(10), 
DR Name VARCHAR(10), State 
County VARCHAR(10), 
DOB 
IN 
VARCHAR(10). 
INT 
FLAG VARCHAR(10) 
);
""
# executing the above SQL code 
cursor.execute(createtable_sql) 
# inserting data into the students table 
insertstudent one sql INSERT INTO name string VALUES (Alex",123457, 20101012, 
20121013, "MVD", Paul, "SA', "USA", 06031987, "A"): cursor.execute(insertstudent.one sq|) 
insertstudent two_sqlINSERT INTO name string VALUES (John",123458, 20101012,
20121013, "MVD", "Paul, TN,IND", 06031987, 'A); 
cursor.execute(insert_student.two_sq) 
insert student_ three.sql NSERT INTO name string VALUES (Mathew', 123459, 20101012, 
20121013, "MVD', "Paul", "WAS, PHIL',06031987, "A);" 
cursor.execute(insert_student_three_sql) 
insert student_three sqlINSERT INTO name string VALUES ("'Matt", 12345, 20101012, 
20121013, "MVD", "Paul", "BOS", "NYC", 06031987, "A)% Cursor.execute(insert_student four sql) 
insert student.three sqlINSERT INTO name string VALUES (Jacob', 1256, 20101012, 
20121013, "MVD", "Paul', 'VIC", "AU'", 06031987, "A"):" 
cursor.execute(insert_student five_sql) 
# saving the changes using commit method of connection 
conn.commit0 
#closing the connection 
conn.close0 
