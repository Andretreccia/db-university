1
mysql> SELECT * FROM students WHERE date_of_birth LIKE '%1990%';

2
mysql> SELECT * FROM courses WHERE cfu > 10;

3
mysql> SELECT * FROM students WHERE YEAR(date_of_birth) < 1991;

4
mysql>  SELECT * FROM courses WHERE period = 'I semestre' and year = 1;

5
mysql> SELECT * FROM exams WHERE hour > '14%' and date = '2020-06-20';

6
mysql> SELECT * FROM degrees WHERE level = 'magistrale';

7
mysql>  SELECT COUNT(id) as `number of departments` FROM departments;

8
mysql> SELECT COUNT(id) as `whithout` FROM teachers WHERE phone IS NULL;