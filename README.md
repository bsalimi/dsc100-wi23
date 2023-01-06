![The_Data_Lifecycle](fig/The_Data_Lifecycle.jpeg)

#   DSC 100: Introduction to Data Management



## Description:

Databases are at the heart of modern commercial application development. Their use extends beyond this to many other environments and domains where large amounts of data must be stored for efficient update, retrieval, and analysis. This course provides a comprehensive introduction to data management, covering topics such as the relational data model, SQL, formal query languages, query evaluation, data storage and indexes, NoSQL databases, conceptual design, integrity constraints, design theory, normal forms, and data quality. Through a combination of lectures, demos, and hands-on exercises, students will gain a strong foundation in database management concepts and practices, with a focus on the use of SQL and the relational model. The course begins with an overview of course organization and an introduction to the relational data model, followed by lessons on SQL basics and different types of joins in SQL. In the following weeks, students will learn advanced SQL queries, formal query languages, and query evaluation. The course also covers topics related to data storage and indexing, including hard disk and file organization, index organization, and creating indexes in SQL. In the latter half of the course, students will study NoSQL databases, conceptual design, integrity constraints, and design theory, culminating in a discussion of normal forms. The course includes a discussion of data quality, including techniques for dealing with missing data and deduplication of records. Upon completion of the course, students will have the skills and knowledge needed to design, implement, and maintain a database system.



## Instructional team:

**Instructor:**

[Babak Salimi](https://bsalimi.github.io/), bsalimi@ucsd.edu

**Course Assistants:**


Baharan Khatami, [skhatami@ucsd.edu](mailto:skhatami@ucsd.edu)

Divija Devarla, [ddevarla@ucsd.edu](mailto:ddevarla@ucsd.edu)


**Lectures**:

Tuesdays and Thursdays at 6:30pm-7:50pm


**Office Hours:**

Babak Salimi, Wedensdays 4:00pm-5:00pm

**Note:** Office hours will be held via Zoom (link can be found on the Canvas calendar). 



**Piazza:** [link](https://piazza.com/ucsd/winter2023/dsc100/) (Requires access code posted on Canvas)

**Have questions? Please email Babak Salimi (bsalimi@ucsd.edu) and at least one of the TAs for questions about logistics. All other questions should be discussed on Piazza.**






## Course Workload
**(subject to change)**

**Homework (60%):** There will be weekly homeworks consisting of written problem-solving and programming assignments (50%) and web quizzes (10%). The purpose of the homeworks is to provide students with the opportunity to apply and practice the concepts and skills learned in the lectures. Homeworks will be more rigorous than the web quizzes and will require students to demonstrate a deeper understanding of the material. The purpose of the web quizzes is to help students reinforce their understanding of the course material by answering review questions based on the previous lectures. The following is a list of the homeworks and web quizzes in the course:

- Homework 1: SQLITE and SQL Basics
- Homework 2: Basic SQL Queries and Installing PostgreSQL
- Homework 3: Advanced SQL and PostgreSQL
- Homework 4: Relational Algebra
- Homework 5: Entity Relationship Diagrams, Conceptual Design
- Homework 6: Constraints and SQL Review
- Web Quiz 1: Data Models and Basic SQL
- Web Quiz 2: SQL Aggregates
- Web Quiz 3: Advanced SQL
- Web Quiz 4: Relational Algebra
- Web Quiz 5: Query Evaluation and Indexes
- Web Quiz 6: Conceptual Design and Design Theory
- Web Quiz 7: Data Quality

**Midterm (15%):** The midterm exam will cover all topics up until Formal Query Languages. It will be held on canvas.

**Final Exam (25%):** The final exam will be comprehensive and will be held on canvas.

**Exam Dates:**

- Midterm Exam: 02/14/2023
- Final Exam: 03/21/2023

**Extra Credit:**

- Some homeworks have extra credit questions.
- Large number of good answers on Piazza.



## Grading Scheme

The grading scheme is a hybrid of absolute and relative grading. The absolute cutoffs are based on your absolute total score. The relative bins are based on your position in the total score distribution of the class. The better grade among the two (absolute-based and relative-based) will be your final grade.

| Grade | Absolute Cutoff (>=) | Relative Bin (Use strictest) |
|-------|----------------------|-------------------------------|
| A+    | 96                   | Highest 5%                    |
| A     | 93                   | Next 10% (5-15)               |
| A-    | 90                   | Next 15% (15-30)              |
| B+    | 83                   | Next 15% (30-45)              |
| B     | 75                   | Next 15% (45-60)              |
| B-    | 70                   | Next 15% (60-75)              |
| C+    | 65                   | Next 5% (75-80)               |
| C     | 60                   | Next 5% (80-85)               |
| C-    | 55                   | Next 5% (85-90)               |
| D     | 50                   | Next 5% (90-95)               |
| F     | < 50                 | Lowest 5%                     |

## Example

Suppose the total score is 82 and the percentile is 33%. So, the relative grade is B-, while the absolute grade is B+. The final grade then is B+.

## Textbook

Although a textbook is not required in the course, the following textbook is optional and recommended. Lecture slides and recorded videos would be sufficient for this class.

Database Systems: The Complete Book, by Hector Garcia-Molina, Jeffrey D. Ullman, and Jennifer Widom. 2nd Edition. Prentice Hall. 2008.

## Canvas

All weekly homework assignments and web quizzes should be turned in via Canvas.

## Communication

All important announcements will be sent through Canvas.

## Piazza

All questions that may be of general interest to the class should be directed to Piazza. You will get your questions answered faster on Piazza than via personal emails to the instructional team, because Piazza is monitored closely by everybody in the class, not just the course staff. You are highly encouraged to answer each other's questions on Piazza (you will get extra credit for the number of good answers on Piazza!) and the 
instructional team would endorse/add to those answers.

## **Calender:**

**(subject to change)**



| Week | Lecture Date | Course Topic |                                                                                                                                                                                                     Lecture Description                                                                                                                                                                                                      | Assignments | Slides | Discussion |                                           Optional Reading                                           |                                                                                                                                                                                                                                                  Lecture Motivation                                                                                                                                                                                                                                   |
|------|--------------|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|--------|------------|----------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1    | Jan 10       | Course organization and Introduction | This lecture will cover the organization and structure of the course, including the syllabus, grading policies, and course materials. We will also introduce the basic concepts of data management and the importance of databases in modern society. | | | | | This lecture will provide an overview of the course and help students understand the goals and objectives of the class. |
|      | Jan 12       | Relational Data Model | This lecture will introduce the relational data model, including a demonstration of the SQLite database management system and an example relational database. We will also discuss the connection to the DataFrame data model and how it is used in data analysis. | Homework 1: SQLITE and SQL Basics| | | | The relational model is a fundamental concept in data management and is the basis for many popular database systems. Understanding the principles of the relational model is essential for data scientists. | 
| 2    | Jan 17       | SQL Basics | This lecture will introduce the basic syntax and semantics of SQL, including the use of the SELECT, FROM, and WHERE clauses to retrieve data from a database. | Web Quiz 1: Data Models and Basic SQL | | | | SQL is a widely used language for interacting with relational databases, and having a strong understanding of SQL is important for data scientists. |
|      | Jan 19       | Joins in SQL Part 1 | This lecture will cover the various types of joins in SQL, including inner, outer, and cross joins. The use of join clauses to combine information from multiple tables will also be discussed. |  | | | | Joins are an important tool for combining data from multiple tables and are used in many complex queries. Understanding how to use joins effectively is essential for working with large datasets. |
| 3    | Jan 24       | Joins in SQL Part 2 | This lecture will continue the discussion of joins in SQL, with a focus on practical examples and a demonstration using the SQLite database management system. | Homework 2: Basic SQL Queries and Installing PostgreSQL | | | | |
|      | Jan 26       | Grouping and Aggregation | This lecture will introduce the concepts of grouping and aggregation in SQL, and show how to write complex analytical queries using these techniques. We will also provide a demonstration of aggregate functions in SQL. | Web Quiz 2: SQL Aggregates| | | | Grouping and aggregation are powerful tools for analyzing and summarizing data, and are frequently used in data analysis and reporting. |
| 4    | Jan 31       | Advanced SQL Queries Part 1 | This lecture will cover complex nested queries and the use of next queries in the WHERE, FROM, and SELECT clauses of an SQL statement. | Homework 3: Advanced SQL and PostgreSQL| | | | Writing complex queries is an essential skill for working with large and complex datasets, and understanding how to do so is crucial for data scientists. |
|      | Feb 2        | Advanced SQL Queries Part 2 | This lecture will continue the discussion of advanced SQL queries, covering expression quantifiers in SQL, monotone versus non-monotone queries, and set operations in SQL. | Web Quiz 3: Advanced SQL| | | | |
| 5    | Feb 7        | Formal Relational Query Languages | This lecture will introduce the basics of relational algebra, extended relational algebra, and their connection to data frames and SQL.  |Web Quiz 4: Relational Algebra Homework 4: Relational Algebra | | | | Understanding Formal Relational languages, such as relational algebra, is crucial for understanding how relational database systems operate. |
|      | Feb 9        | Query Evaluation | This lecture will review the steps involved in query evaluation and discuss the implementation of query operators in database systems. We will also compare pipeline versus blocking approaches to query evaluation. | | | | | Query evaluation is a crucial aspect of database performance and understanding how queries are executed is important for optimizing database systems. |
|  6   | Feb 14       | Data Storage, Indexes and Size Estimation Part 1 | This lecture will cover the basics of data storage, including the structure of hard disks and file systems, as well as the use of indexes to improve the performance of database queries. We will also discuss the differences between clustered and unclustered indexes. | | | | | Data storage is a critical aspect of database management, and understanding the different options and trade-offs is essential for optimizing the performance of a database system. |
|     | Feb 16       | Midterm Exam |  | | | | |  |
|  7    | Feb 21       | Data Storage, Indexes and Size Estimation Part 2 | This lecture will continue the discussion of data storage and indexes, with a focus on creating indexes in SQL and the use of size estimation techniques to optimize queries. | Web Quiz 5: Query Evaluation and Indexes | | | | |
|     | Feb 23       | Conceptual Design | The purpose of the conceptual design phase is to build a conceptual model based upon the previously identified requirements, but closer to the final physical model. A commonly-used conceptual model is called an entity-relationship model. This lecture will introduce the concepts of conceptual design and entity-relationship modeling, and show how to use these tools to design a database. | Homework 5: Entity Relationship Diagrams, Conceptual Design| | | | Conceptual design is an important step in the database design process, and understanding the principles of entity-relationship modeling is essential for creating a well-structured database. |
|      | Feb 25       | Integrity Constraints | This lecture will cover the concept of integrity constraints in database design, including the use of primary and foreign keys to enforce relationships between entities. We will also discuss how to define constraints on an entity-relationship diagram and how to express them in SQL. | Web Quiz 6: Conceptual Design and Design Theory |  | | | Understanding how to use integrity constraints is essential for maintaining the correctness and consistency of data in a database, and is an important skill for data scientists. |
| 8    | Feb 23       | Design Theory | This lecture will cover the database design process, including the importance of functional dependencies and normal forms. We will also introduce the implication problem and the closure algorithm, which are used to determine functional dependencies. | | | | | Design theory is a fundamental concept in database design, and understanding the principles of normalization and functional dependencies is essential for creating a well-structured database. |
|      | Feb 25       | Normal Forms |This lecture will introduce the concept of Boyce-Codd normal form (BCNF) in database design. We will discuss the importance of BCNF in ensuring the integrity and performance of a database, and show how to apply BCNF to a design. | | | | | Normalization is a technique used in database design to minimize redundancy and eliminate anomalies. It is an essential skill for designing effective and efficient databases.|
| 9    | Mar 2        | NoSQL Databases | This lecture will introduce the concept of NoSQL databases, including the differences between OLAB and OLTP systems, the motivations for using NoSQL, and the architecture of RDBMS systems. We will also discuss partitioning and replication, and compare the relational model to NoSQL. | Homework 6: Constraints and SQL Review| | | | NoSQL databases are a popular alternative to traditional relational database systems, and Understanding the differences and trade-offs between NoSQL and traditional relational databases is important for data scientists. |
| 10   | Mar 7        | Data Quality Part 1 | This lecture will introduce the concept of data quality and its common dimensions, then it will focus on simple tricks to deal with missing data in SQL.  | | | | | Data quality is an important concern in database management, and understanding how to identify and address issues of poor quality is essential for ensuring the accuracy and reliability of a database. |
|      | Mar 9        | Data Quality Part 2 | This lecture will focus on entity deduplication, which is the process of identifying and merging records that refer to the same real-world entity. We will discuss different approaches to entity matching and the trade-offs involved. | Web Quiz 7: Data Quality| | | |  Entity deduplication is a crucial step in ensuring the accuracy and completeness of data within a database. It involves identifying and merging duplicate records, which can help to improve the integrity and reliability of the database as a whole.




*Note:*  Some slides are adopted from the UW database group. 


## Related Groups:

- [UCSD Database Group](https://dbucsd.github.io/)

- [SIGMOD (Special Interest Group on Management of Data)](https://www.google.com/url?q=https%3A%2F%2Fsigmod.org%2F&sa=D&sntz=1&usg=AFQjCNEv9sM8CpuOZ7oxWFX_20353W6NZw)

- [VLDB (Very Large Data Base Endowment Inc.)](https://www.google.com/url?q=https%3A%2F%2Fwww.vldb.org%2F&sa=D&sntz=1&usg=AFQjCNEN7a3TJIOhpq3OC7bw9DKWHhki-w)

- [PODS (Symposium on Principles of Database Systems)](https://www.google.com/url?q=https%3A%2F%2Fsigmod.org%2Fpods%2F&sa=D&sntz=1&usg=AFQjCNEy52V8Padws9vrgz2GoFYinNgG9Q)

- [ICDT(IEEE International Conference on Data Engineering)](http://ieee-icde.org/)

- [CIDR (Conference on Innovative Data Systems Research)](http://www.google.com/url?q=http%3A%2F%2Fcidrdb.org%2F&sa=D&sntz=1&usg=AFQjCNHZ5MTU545Lei9xcYfQR9fHHLan5w)



