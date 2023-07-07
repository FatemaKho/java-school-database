<<<<<<< HEAD
# Code Project: SQL Queries
## Overview

 write SQL statements to retrieve specific data from an existing database.

### Database Information

The database for this assignment is embedded in the code provided in the GitHub repository, so you do not need to set up the database.

To see the database structure and the existing data in each table, see the page at <a href="DatabaseInformation.md">DatabaseInformation.md</a>.

> #### ⚠ Important!
>
> Because of how the database is set up in the program, the data in the database will reset each time you build the code. Changes to the data (including insertions, updates, and deletions) will not persist between builds. For this reason, you should complete the tasks in the order listed, because later queries may depend on earlier queries.

### Additional Tips

Writing queries that run using Java's sql library, rather than running directly in an RDBMS like MySQL. Because you are working with Java, you must follow these guidelines:

- Because the SQL statement is inside double quotation marks (" "), any string values must be inside single quotation marks (' ').
- Strings are case sensitive, so `'john smith'` is not the same as `'John Smith'`.
- Line breaks are permitted but optional. If you hit the ENTER key while keying a SQL statement into the Java statement, the IDE may add additional characters such as extra quotation marks or newline breaks (`/n`). These will not affect how the SQL statement runs.
- Semi-colons are optional.
- The Java tests look at the output of each query to determine whether or not the tests pass. While the SQL syntax must produce the expected results, variation in the syntax is allowed.

You may, if you wish, test the SQL statements in MySQL Workbench before adding them to the Java statement. 

* The schema and data for the complete database are included inside the Resource folder in the Java project. These can be used to build the database in MySQL.


1. `allStudents()`: Write a query that returns all students (first name, last name only) sorted by last name.
2. `CS_Courses()`: Write a query that lists the course code and course name for all courses in the Computer Science department.
3. `teacherCountByDept()`: Write a query that displays the department and the total number of teachers assigned to each department. Name the aggregate field `teacherCount`.
4. `studentsPerClass()`: Write a query that lists the course code and course description for each course, with the number of students enrolled in each course.
5. This step includes two parts. Both parts must be completed to pass the test.
   - Part 1: `addStudent()`: Write a query to add the student Robert Dylan to the student table.
   - Part 2: `addStudentToClass()`: Write a query to add Robert Dylan to CS148.

6. `editCourseDescription()`: Write a query to change the course description for course CS305 to `Advanced Python with Flask`.
7. `deleteTeacher()`: Write a query to remove Lewis Carroll as a teacher.


