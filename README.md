Download Link: https://assignmentchef.com/product/solved-cs3431-homework-2
<br>
<strong><u>Problem 1:</u></strong>

Draw the ER diagram using an ISA relationship for the following example:

<em>Assume in a company, we have two kinds of staff, namely salaried-employees and contract-employees. Both have a unique identifier SSN and a name. For salaried-employees we keep track of their yearly salary as well as the department to which they have been assigned to.  For contract-employees, we keep track of the number of hours they have a contract for, the hourly rate of pay, as well as the project number for the project in charge of this contract.</em>

Write the DDL for <strong>three</strong> different possible schemas that map your ER Diagram into a relational model using one, two or three tables. For each of these three schemas, compare the redundancy, flexibility, and relative cost of querying. Note which schema you think is the best overall. Do not forget to use keys and foreign keys, as appropriate.

Next, consider the “none-overlap constraint among sibling classes” constraint that further restricts the type of ISA relationship being modeled. Discuss if these semantics could be enforced on any of your three designs using primary keys, foreign keys, unique and NOT NULL constraints.

<strong><u>Problem 2: </u></strong>

Assume an employee entity with attributes including Name, SSN, salary, and job-skill. Let SSN be the primary key of employee entities, while the Name attribute is not necessarily unique. Assume employee entities tend to have multiple different job skills, such as programming, networking, communication, etc. In other words, “skills” is a multi-valued attribute. In addition, an employee in your database may be the manager-of another employee in your database. Let us assume here that for each employee there would be at most one direct manager within the database, while an employee in our database may be in charge of (manager-of) up to 100 different employees. For each employee that a manager is managing successfully, she will be assigned a bonus increase in addition to her regular salary.

<ol>

 <li>Model the above requirements using an ER diagram.</li>

 <li>Translate your ER model into a relational schema using SQL DDL statements. Using the guidelines we discussed in class, include reducing the number of relations whenever appropriate.</li>

 <li>Enter your DDL statements into ORACLE   to verify that they are correct.  Develop some data set for your database application, and load your data into your schema. Show us the log (using spool off/on) of the above script of you working with ORACLE DBMS, i.e., of   creating your schema and loading data into it.</li>

 <li>State additional assumptions that you have made, if any.</li>

 <li>Provide a brief discussion justifying your chosen mapping strategy for the different cases of mapping that you encounter.</li>

 <li>Provide a listing of any information, including constraints and cardinalities that could not be represented in the relational model using the basic SQL constraints like primary keys, foreign keys, unique and not null.</li>

</ol>

<strong><u>Problem 3 (University Database) </u></strong>

Create a Relational Model (the CREATE TABLE statements) for the following database:

<ul>

 <li>We have students; each student has a unique Id, name, address, gender, and overall GPA (has default value of 0).</li>

 <li>Each student must have one major (mandatory attribute) and optionally one minor.</li>

 <li>The model must check that the gender takes values either “Male” or “Female”</li>

 <li>We have courses, each course has a unique CourseId, title, and number of credits</li>

 <li>Students will register in courses in certain semesters. We need to keep track of the grade (number, NOT letter) that a student has received in a given course. The model should allow a student to take the same course in different semesters.</li>

</ul>




Your CREATE TABLE statements should clearly indicate the following: 1) The attribute names and their data types (choose appropriate types), 2) The primary keys in each table, 3) The NULL (or NOT NULL) and the DEFUALT constraints, 4) The CHECK domain constrains, and 5) The foreign key constraints.


