# java-school-database

Using what I learned to create a Java web service and implement CRUD capabilities, dependency injection, and MVC structure (including the service layer), I produced a working CRUD-enabled web service. Below has more information as to how it is structured.

-Map data from the database to the Course, Student, and Teacher objects. (This has an H2 database), URL provided in application properties.
-For packages, use the MVC layer including the service layer for validation.
-Write code to implement the CourseDao, StudentDao, and TeacherDao interfaces.
-Write code to implement the CourseServiceInterface, StudentServiceInterface, and TeacherServiceInterface.

Create CRUD endpoints for each of the following:

Course Controller:
Return a list of all courses
Return a course by ID
Add a new course
Edit an existing course
Delete a course

Student Controller:
Return a list of all students
Return a student by ID
Add a new student
Edit an existing student
Delete a student
Delete a student from a course
Add a student to a course

Teacher Controller:
Return a list of all teacher
Return a teacher by ID
Add a new teacher
Edit an existing teache
Delete a teacher
