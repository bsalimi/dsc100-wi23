![The_Data_Lifecycle](fig/The_Data_Lifecycle.jpeg)

# DSC 100: Introduction to Data Management



## Description:

Databases are at the heart of modern commercial application development. Their use extends beyond this to many other environments and domains where large amounts of data must be stored for efficient update, retrieval, and analysis. This course provides a comprehensive introduction to data management, covering topics such as the relational data model, SQL, formal query languages, query evaluation, data storage and indexes, NoSQL databases, conceptual design, integrity constraints, design theory, normal forms, and data quality. Through a combination of lectures, demos, and hands-on exercises, students will gain a strong foundation in database management concepts and practices, with a focus on the use of SQL and the relational model. The course begins with an overview of course organization and an introduction to the relational data model, followed by lessons on SQL basics and different types of joins in SQL. In the following weeks, students will learn advanced SQL queries, formal query languages, and query evaluation. The course also covers topics related to data storage and indexing, including hard disk and file organization, index organization, and creating indexes in SQL. In the latter half of the course, students will study NoSQL databases, conceptual design, integrity constraints, and design theory, culminating in a discussion of normal forms. The course includes a discussion of data quality, including techniques for dealing with missing data and entity deduplication. Upon completing the course, students will be equipped with the skills and knowledge necessary for designing, querying, and maintaining a relational database.



## Instructional team:

**Instructor:**

[Babak Salimi](https://bsalimi.github.io/), bsalimi@ucsd.edu

**Course Assistants:**


Baharan Khatami, [skhatami@ucsd.edu](mailto:skhatami@ucsd.edu)

Divija Devarla, [ddevarla@ucsd.edu](mailto:ddevarla@ucsd.edu)

Pragna Elavarthi   [pelavarthi@ucsd.edu](mailto:pelavarthi@ucsd.edu)

Megha Agarwal [meagarwal@ucsd.edu](mailto:meagarwal@ucsd.edu)


**Lectures**:

Tuesdays and Thursdays at 6:30pm-7:50pm


**Note:** The lectures for this course will be automatically recorded and made available for students to watch at their convenience. While attending the lectures in person is not required, it is highly recommended as it provides an opportunity to ask questions and interact with the instructor and other students. The recordings are meant to be a supplement to the in-person lectures and should not be used as a replacement for attendance


**Office Hours:**

Babak Salimi, Wedensdays 4PM - 5PM

Baharan Khatami, Fridays 3PM - 4PM

Divija Devarla, Thursdays 9AM - 10AM

Pragna Elavarthi,   Mondays 10AM - 11AM

Megha Agarwal, Tuesdays 4PM - 5 PM

**Note:** Office hours will be held via Zoom (link can be found on the Canvas calendar). 



**Piazza:** [link](https://piazza.com/ucsd/winter2023/dsc100/) (Requires access code posted on Canvas)

**Have questions? Please email Babak Salimi (bsalimi@ucsd.edu) and at least one of the TAs for questions about logistics. All other questions should be discussed on Piazza.**






## Course Workload
**(subject to change)**

**Homework (60%):** There will be weekly homeworks consisting of written problem-solving and programming assignments (50%) and web quizzes (10%). The purpose of the homeworks is to provide students with the opportunity to apply and practice the concepts and skills learned in the lectures. Homeworks will be more rigorous than the web quizzes and will require students to demonstrate a deeper understanding of the material. The purpose of the web quizzes is to help students reinforce their understanding of the course material by answering review questions based on the previous lectures. The following is a list of the homeworks and web quizzes in the course:

- Homework 1: SQLITE and SQL Basics
- Homework 2: Basic SQL Queries
- Completion of Postgres Setup for Homework 3
- Homework 3: Advanced SQL and PostgreSQL
- Homework 4: Relational Algebra
- Homework 5: Entity Relationship Diagrams and Conceptual Design
- Homework 6: Constraints and SQL Review
- Web Quiz 1: Data Models and Basic SQL
- Web Quiz 2: SQL Aggregates
- Web Quiz 3: Advanced SQL
- Web Quiz 4: Relational Algebra
- Web Quiz 5: Query Evaluation and Indexes
- Web Quiz 6: Conceptual Design and Design Theory
- Web Quiz 7: Data Quality

**Due dates:**  Please note that the due dates for both the homework assignments and web quizzes can be found on the Canvas calendar. Additionally, the homework assignment due dates are also available on the course webpage calendar (below). Web quizzes are due on Mondays of the following week in which they are released.

**Note:** Homework assignments can be completed in teams of size 2. This means that you can work with one other student to complete the assignment and submit a single solution. It is expected that each member of the team will contribute equally to the solution and have a thorough understanding of the material. Collaboration is encouraged as it can help deepen understanding and facilitate learning, but it is important that all team members understand the work being submitted and are able to explain it if necessary. Plagiarism and cheating will not be tolerated and will result in disciplinary action.

**Late Day Policy:** You have up to 3 late days to use on homework assignments. These late days can be used in 24-hour chunks. You can only use one late day on each assignment. Late days are meant to be a safety net and should not be used as a convenience. It is expected that you will not need to use your late days and that you will submit all assignments on time. If you use all of your late days, it is likely that you are not managing your time effectively and will need to adjust your study habits. **Please note that no excuses for not submitting assignments on time will be accepted once you have exhausted your late days.**


**Midterm (15%):** The midterm exam will cover all topics up until Formal Query Languages. It will be held on canvas.

**Final Exam (25%):** The final exam will be comprehensive and will be held on canvas.

Both Midterm and Final exam will be held remote.

**Exam Dates:**

- Midterm Exam: 02/16/2023
- Final Exam: 03/21/2023

**Extra Credit:**

- Some homeworks have extra credit questions.
- Large number of good answers on Piazza.



## **Calender:**

**(subject to change)**





| Week | Lecture Date | Course Topic |                                                                                                                                                                                                     Lecture Description                                                                                                                                                                                                      | Assignments | Slides | Discussion |                                           Optional Reading                                           |                                                                                                                                                                                                                                                  Lecture Motivation                                                                                                                                                                                                                                   |
|------|--------------|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|--------|------------|----------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1    | Jan 10       | Course organization and Introduction | This lecture will cover the organization and structure of the course, including the syllabus, grading policies, and course materials. We will also introduce the basic concepts of data management and the importance of databases in modern society. | | [Slides](https://drive.google.com/file/d/1k9fcrXxqJkzCYOsGe2bcA56bZiEWrFe8/view?usp=sharing) [Demo 1: Relational Data Model](https://drive.google.com/file/d/1QMaUIn5CEXc12PzHqc1zi2y5ckAiGSQ9/view?usp=sharing)| | <em> Text Book: </em> Sec. 2.1      <br>           <em> Blog posts: </em>  [Data Management: What It Is, Importance, And Challenges](https://www.tableau.com/learn/articles/what-is-data-management#:~:text=Data%20management%20helps%20minimize%20potential,market%20changes%20and%20customer%20needs.) | This lecture will provide an overview of the course and help students understand the goals and objectives of the class. |
|     | Jan 12       | Relational Data Model | This lecture will introduce the relational data model, including a demonstration of the SQLite database management system and an example relational database. We will also discuss the connection to the DataFrame data model and how it is used in data analysis. | **Homework 1 - release:** SQLITE and SQL Basics| [Slides](https://drive.google.com/file/d/1-3i27UrzE3-F3tfqEGlaxHa87gmUO180/view?usp=sharing) || <em> Text Book: </em> Sec. 2.2, 2.3  <em> Blog posts: </em>  [Why You Should Learn SQL](https://medium.com/365datascience/why-you-should-learn-sql-a8662ac145f0),  [Preventing the Death of the Dataframe](https://towardsdatascience.com/preventing-the-death-of-the-dataframe-8bca1c0f83c8#:~:text=Dataframe%20Data%20Model.,runtime%20if%20it%20is%20needed.)  | The relational model is a fundamental concept in data management and is the basis for many popular database systems. Understanding the principles of the relational model is essential for data scientists. | 
|      | Jan 16       | |  | | | [Introduction to SQL](https://drive.google.com/file/d/1XcMW2ZXVeXlglBRo8OhorFb4DJv6fWkV/view?usp=sharing) | | 
| 2    | Jan 17       | SQL Basics | This lecture will introduce the basic syntax and semantics of SQL, including the use of the SELECT, FROM, and WHERE clauses to retrieve data from a database. | Task: Completion of Postgres Setup for Homework 3 Web Quiz 1: Data Models and Basic SQL | [Slide](https://drive.google.com/file/d/1lNWvBlX0WCw4G22KVG5fbzDjSAqvhC5-/view?usp=sharing) <br>   [Demo 2: SQL Basics](https://drive.google.com/file/d/18NHZ9ktThniIHSzPxO-OyJm1vrgGYoiN/view?usp=sharing)| | | SQL is a widely used language for interacting with relational databases, and having a strong understanding of SQL is important for data scientists. |
|      | Jan 19       | Joins in SQL Part 1 | This lecture will cover the various types of joins in SQL, including inner, outer, and cross joins. The use of join clauses to combine information from multiple tables will also be discussed. |  | [Slide](https://drive.google.com/file/d/1lRt8mmzpMs08bmHKj0JbS_CaKemfurU5/view?usp=sharing) | | | Joins are an important tool for combining data from multiple tables and are used in many complex queries. Understanding how to use joins effectively is essential for working with large datasets. |
|      | Jan 23      |  |  | | [Slides](https://drive.google.com/drive/folders/1ykKfWQV5q4ySDMSqD9CwjbXmPgspoSOz)|[SQL Basics and Joins](https://drive.google.com/drive/folders/1ykKfWQV5q4ySDMSqD9CwjbXmPgspoSOz) | |  
 3    | Jan 24       | Joins in SQL Part 2 | This lecture will continue the discussion of joins in SQL, with a focus on practical examples and a demonstration using the SQLite database management system. | **Homework 2 - release:** Basic SQL Queries  | [Slide](https://drive.google.com/file/d/1lRt8mmzpMs08bmHKj0JbS_CaKemfurU5/view?usp=sharing) [Demo 3: Joins in SQL](https://colab.research.google.com/drive/1ZdWDQ8cTOE0x1IjVtaDhDhAVPdC5Bkpj?usp=sharing) | | | |
|      | Jan 26       | Grouping and Aggregation | This lecture will introduce the concepts of grouping and aggregation in SQL, and show how to write complex analytical queries using these techniques. We will also provide a demonstration of aggregate functions in SQL. | Web Quiz 2: SQL Aggregates| [Slides](https://drive.google.com/file/d/1lmX5lwEsFPcThcu23lIvF8JqEubzEY0W/view?usp=sharing) <br> [Demo 4: AGGREGATES IN SQL](https://drive.google.com/file/d/1X53PbcIUrNSM5uuj8_4JI5UsC7FiEAgr/view?usp=sharing) <br>  [Demo 5: AGGREGATES IN SQL (real data)](https://colab.research.google.com/drive/1sEpPyz-DRzL9o26KoOlrW9dWXZlFa6Y3?usp=sharing)  | | | Grouping and aggregation are powerful tools for analyzing and summarizing data, and are frequently used in data analysis and reporting. |
|      | Jan 30     |  |  | | [Slides](https://drive.google.com/file/d/1o3A0ddzXkEaD4WcOXfQBxsTaoEgZp4ME/view?usp=share_link)|SQL Group and Aggregation | [SQL Group and Aggregation](https://drive.google.com/drive/folders/1DrGmMzMsKY_aUbuQp3k28knepA8SUfyj?usp=sharing)| 
| 4    | Jan 31       | Advanced SQL Queries Part 1 | This lecture will cover complex nested queries and the use of next queries in the WHERE, FROM, and SELECT clauses of an SQL statement. | **Homework 3 - release:** Advanced SQL and PostgreSQL| [Slide](https://drive.google.com/file/d/1m-QbR2XKO5fsh8sAldZ3LE15I0Z0j491/view?usp=sharing)  | | | Writing complex queries is an essential skill for working with large and complex datasets, and understanding how to do so is crucial for data scientists. |
|      | Feb 2        | Advanced SQL Queries Part 2 | This lecture will continue the discussion of advanced SQL queries, covering expression quantifiers in SQL, monotone versus non-monotone queries, and set operations in SQL. | Web Quiz 3: Advanced SQL|    [Slides](https://drive.google.com/file/d/1-5CbABtZH1NoeVwudMQJB6W3A-T8bMtT/view?usp=sharing) <br> [Demo 6:  Nested Queries and Set Oprations In SQL](https://drive.google.com/file/d/18xdwUBWsBcZJEL0jLWCypPkV-G-zNAS6/view?usp=sharing) | | | |
|      | Feb 6     |  |  | |[Slides](https://drive.google.com/file/d/1hRnnUZ26i1BU25LdYM3xmVkUK3s0Le1c/view?usp=sharing) | [Nested Queries](https://drive.google.com/file/d/1X0VyV-4RHzvCpoYcDLCLGMUo4j-XS18p/view?usp=sharing) | | 
| 5    | Feb 7        | Formal Relational Query Languages Part 1 | This lecture will introduce the basics of relational algebra, extended relational algebra, and their connection to data frames and SQL.  |**Homework 4 - release:** Relational Algebra |[Slides](https://drive.google.com/file/d/1m-dxrdhZZWTHXZ1KeDDUYKso1IgnMLAt/view) | | | Understanding Formal Relational languages, such as relational algebra, is crucial for understanding how relational database systems operate. |
|      | Feb 9        | Formal Relational Query Languages Part 2 | This lecture continues our discussion on the connection between relational algebra and SQL. |Web Quiz 4: Relational Algebra  | | | |  |
|      | Feb 13    |   |  | | | Midterm Sample Questions <br /> [Part I](https://drive.google.com/file/d/16LdnSuNeWsy6_H6hrhdNf8ZR7_X6RmVC/view?usp=sharing) <br /> [Part II](https://drive.google.com/file/d/1UKu_qZwJ4E1Itv_-NnVBI5i2DSyLCeyF/view?usp=sharing)| | 
|       | Feb 14    |  Interactive Data Analysis Using SQL |  | | |  | | 
|      | Feb 16       | Midterm Exam |  | | | | |  |
|      | Feb 20    |   |  | |[Slides](https://drive.google.com/drive/folders/1ykKfWQV5q4ySDMSqD9CwjbXmPgspoSOz) |Relational Algebra, Algebra of Bags | | 
|  7   | Feb 21       | Data Storage, Indexes and Size Estimation Part 1 | This lecture will cover the basics of data storage, including the structure of hard disks and file systems, as well as the use of indexes to improve the performance of database queries. We will also discuss the differences between clustered and unclustered indexes. || [Slide](https://drive.google.com/file/d/1sLmMiFQvFp0l7Uob0NPkh5x72s40niX0/view?usp=sharing) [Recording](https://drive.google.com/file/d/1P1E6wvCxhL3j6aON0zcQBkYXMixzlWmQ/view?usp=sharing)| | | Data storage is a critical aspect of database management, and understanding the different options and trade-offs is essential for optimizing the performance of a database system. |
|      | Feb 23       | Data Storage, Indexes and Size Estimation Part 2 | This lecture will continue the discussion of data storage and indexes, with a focus on creating indexes in SQL and the use of size estimation techniques to optimize queries. |    |[Recording](https://drive.google.com/file/d/1hnYWuXWyVPWvxXtBp6XSDI-xxBlaVDOe/view?usp=sharing) | | | |
|       | Feb 27    |   |  | | |Database indexes, Conceptual Design, ER Diagram | | 
|   8  | Feb 28       | Conceptual Design | The purpose of the conceptual design phase is to build a conceptual model based upon the previously identified requirements, but closer to the final physical model. A commonly-used conceptual model is called an entity-relationship model. This lecture will introduce the concepts of conceptual design and entity-relationship modeling, and show how to use these tools to design a database. | Web Quiz 5: Query Evaluation and Indexes **Homework 5 - release:** Entity Relationship Diagrams, Conceptual Design| [E/R Diagrams](https://drive.google.com/open?id=1t8NDCzgGApJr_yxrmk5giR6f3zZH7BgX&authuser=bsalimi%40ucsd.edu&usp=drive_fs) [Constraints](https://drive.google.com/file/d/1sqynJ4wOK15tfJxqwqBigEaMRggnUKSc/view?usp=sharing) | | | Conceptual design is an important step in the database design process, and understanding the principles of entity-relationship modeling is essential for creating a well-structured database. 
 | Mar 2        | Design Theory | This lecture will cover the database design process, including the importance of functional dependencies and normal forms. We will also introduce the implication problem and the closure algorithm, which are used to determine functional dependencies. | | | | | Design theory is a fundamental concept in database design, and understanding the principles of normalization and functional dependencies is essential for creating a well-structured database. |
|       | Mar 6    |   |  | | |Integrity Constraints, Database Design Theory | | 
|  9    | Mar 7      | Normal Forms |This lecture will introduce the concept of Boyce-Codd normal form (BCNF) in database design. We will discuss the importance of BCNF in ensuring the integrity and performance of a database, and show how to apply BCNF to a design. | | | | | Normalization is a technique used in database design to minimize redundancy and eliminate anomalies. It is an essential skill for designing effective and efficient databases.|
|     | Mar 9        | NoSQL Databases | This lecture will introduce the concept of NoSQL databases, including the differences between OLAB and OLTP systems, the motivations for using NoSQL, and the architecture of RDBMS systems. We will also discuss partitioning and replication, and compare the relational model to NoSQL. | **Homework 6-release:** Constraints and SQL Review| | | | NoSQL databases are a popular alternative to traditional relational database systems, and Understanding the differences and trade-offs between NoSQL and traditional relational databases is important for data scientists. |
|      | Mar 13    |   |  | | |Normal Forms | | 
| 10   | Mar 14       | Data Quality Part 1 | This lecture will introduce the concept of data quality and its common dimensions, then it will focus on simple tricks to deal with missing data in SQL.  | | | | | Data quality is an important concern in database management, and understanding how to identify and address issues of poor quality is essential for ensuring the accuracy and reliability of a database. |
|      | Mar 16        | Data Quality Part 2 | This lecture will focus on entity deduplication, which is the process of identifying and merging records that refer to the same real-world entity. We will discuss different approaches to entity matching and the trade-offs involved. | Web Quiz 7: Data Quality| | | |  Entity deduplication is a crucial step in ensuring the accuracy and completeness of data within a database. It involves identifying and merging duplicate records, which can help to improve the integrity and reliability of the database as a whole.
|      | Mar 21       | Final Exam |  | | | | |  |




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



*Note:*  Some slides are adopted from the UW database group. 


## Related Groups:

- [UCSD Database Group](https://dbucsd.github.io/)

- [SIGMOD (Special Interest Group on Management of Data)](https://www.google.com/url?q=https%3A%2F%2Fsigmod.org%2F&sa=D&sntz=1&usg=AFQjCNEv9sM8CpuOZ7oxWFX_20353W6NZw)

- [VLDB (Very Large Data Base Endowment Inc.)](https://www.google.com/url?q=https%3A%2F%2Fwww.vldb.org%2F&sa=D&sntz=1&usg=AFQjCNEN7a3TJIOhpq3OC7bw9DKWHhki-w)

- [PODS (Symposium on Principles of Database Systems)](https://www.google.com/url?q=https%3A%2F%2Fsigmod.org%2Fpods%2F&sa=D&sntz=1&usg=AFQjCNEy52V8Padws9vrgz2GoFYinNgG9Q)

- [ICDT(IEEE International Conference on Data Engineering)](http://ieee-icde.org/)

- [CIDR (Conference on Innovative Data Systems Research)](http://www.google.com/url?q=http%3A%2F%2Fcidrdb.org%2F&sa=D&sntz=1&usg=AFQjCNHZ5MTU545Lei9xcYfQR9fHHLan5w)



