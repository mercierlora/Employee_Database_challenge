# Employee_Database_challenge
Purpose of our project
The purpose of this project is to analyze the number of retiring employees by title and identify which employees are eligible to to participate in the mentorship program. Our retiring employees by title information will show the titles of all employees born between January, 1 1952 and December, 31 1955. First create a query that retrieved the emp_no, first_name and last_name columns from the employees table and retrieved the title,from_date and to_date columns of the titles table in pewlett-hackard query. Join both of these table on the primary key,filtered the data by birth_date and put the information into a new table. For the next two parts of deliverable 1 create a unique_titles table to find the first occurance of the emp_no in the new table by using the DISTINCT ON function and for the last part of the deliverable did ORDER BY COUNT to show us the total number of each title from the unique_titles table that was created. The second deliverable wrote a query that retrieved columns from our employees and dept_emp table, filtered data on current employees born in 1965 then ordered the table by emp_no.

The Results
With the retirment_titles table I was able to see every eligible for retirement employee and how long they have worked at each position over the course of their career.

The unique titles table that I created is showing the most recent title for employees of retirment age.

Our retiring_titles shows us the a majority of the employees of retirment age (57,668/90,398 = 64%) have senior titles.

![image](https://user-images.githubusercontent.com/100738861/181935455-fe2fc5e5-26f9-45ae-b6c4-c3fb8c9c5636.png)

The final part of the project shows mentorship eligibility, if you look at the head of the new csv - you can see that most of these employees have senior titles.
![image](https://user-images.githubusercontent.com/100738861/181935486-dcc0967c-48ca-4d3b-b166-37f9cfb3d7b9.png)

