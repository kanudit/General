SELECT * FROM students; 

SELECT first_name from students;
SELECT last_name from students;
SELECT first_name FROM students where id = 2;
SELECT first_name FROM students where last_name = 'Benichou' and first_name = 'Marc';
SELECT first_name FROM students where last_name = 'Benichou' or first_name = 'Marc';
SELECT first_name FROM students where first_name LIKE '%a%';
SELECT first_name FROM students where first_name LIKE 'a%';
SELECT first_name FROM students where first_name LIKE '%a';
SELECT first_name FROM students WHERE SUBSTR(first_name, 3, 1) = 'a'
<!-- cant -->

SELECT * FROM students WHERE dob >= '2000-01-01'

SELECT * FROM students WHERE id < 5 ORDER BY last_name ASC;
-- Select * FROM students 
SELECT  MAX(dob) FROM students ;

SELECT * from students WHERE id NOT BETWEEN 1 AND 2
