# ST445 Managing and Visualizing Data


### Michaelmas Term 2017

### Instructors

* [Kenneth Benoit](k.r.benoit@lse.ac.uk), Department of Methodology.  *Office hours*: By appointment, COL 8.11
* [Milan Vojnovic](M.Vojnovic@lse.ac.uk), Department of Statistics.  *Office hours*: TIME, BLDG

### Course Information

* Lectures on Tuesdays 10:00–12:00 in CLM.2.02
* Classes on Thursdays 13:00–14:30 in TW2.4.02

No lectures or classes will take place during School Reading Week 6.


### Course Description

This course will cover the principles of digital methods for storing and structuring data, including data types, relational and non-relational database design, and query languages. Students will learn to build, populate, manipulate and query databases based on datasets relevant to their fields of interest. The course will also cover workflow management for typical data transformation and cleaning projects, frequently the starting point and most time-consuming part of any data science project. This course uses a project- based learning approach towards the study of online publishing and group -based collaboration, essential ingredients of modern data science projects. The coverage of data sharing will include key skills in on-line publishing, including the elements of web design, the technical elements of web technologies and web programming, as well as the use of revision- control and group collaboration tools such as GitHub. Each student will build one or more interactive website based on content relevant to his/her domain -related interests, and will use GitHub for accessing and submitting course materials and assignments.

In this course, we introduce principles and applications of the electronic storage, structuring, manipulation, transformation, extraction, and dissemination of data. This includes data types, database design, data base implementation, and data analysis through structured queries. Through joining operations, we will also cover the challenges of data linkage and how to combine datasets from different sources. We begin by discussing concepts in fundamental data types, and how data is stored and recorded electronically. We will cover database design, especially relational databases, using substantive examples across a variety of fields. Students are introduced to SQL through MySQL, and programming assignments in this unit of the course will be designed to insure that students learn to create, populate and query an SQL database. We will introduce NoSQL using MongoDB and the JSON data format for comparison. For both types of database, students will be encouraged to work with data relevant to their own interests as they learn to create, populate and query data. In the final section of the data section of the course, we will step through a complete workflow including data cleaning and transformation, illustrating many of the practical challenges faced at the outset of any data analysis or data science project.


### Organization

This course is an introduction to the fundamental concepts of data and data visualization for students and assumes no prior knowledge of these concepts.  

The course will involve 20 hours of lectures and 15 hours of computer workshops in the MT. 	


### Prerequisites

No prior experience with programming is required.


### Software

TWe will use some tools, notably SQLLite, R, and Python, but these will be used in coordination with MY470 (Computer Programming) where their use will be covered more formally.  Lectures and assignments will be posted on Github, Students are expected to use Github also to submit problem sets and final exam.

### Materials

The main course texts will be:

The main course texts will be:
*	Chodorow, Kristina MongoDB: The Definitive Guide, 2nd Edition O’Reilly 2013. Churcher, Clare. Beginning Database Design: From Novice to Professional. Apress, 2007.
*	Tahaghoghi, Seyed M. and Hugh E. Williams. Learning MySQL. O'Reilly, 2006. Karumanchi, Narasimha. Data Structures and Algorithms Made Easy: Data Structure and Algorithmic Puzzles, Second Edition. CreateSpace Independent Publishing Platform, 2011.
*	Lee, Kent. Data Structures and Algorithms with Python. Springer, 2015.
*	Lake, Peter. Concise Guide to Databases: A Practical Introduction. Springer, 2013.
*	Nield, Thomas. Getting Started with SQL: A hands-on approach for beginners. O’Reilly, 2016.
*	Byron, Angela and Addison Berry, Nathan Haug, Jeff Eaton, James Walker, Jeff Robbins Using Drupal: Choosing and Configuring Modules to Build Dynamic Websites. O'Reilly Media, 2008.
*	Duckett, Jon HTML and CSS: Design and Build Websites New York: Wiley, 2011.
*	Duckett, Jon JavaScript and JQuery: Interactive Front-End Web Development New York: Wiley, 2014.
*	Rice, Dylan. Twitter Bootstrap In Your Pocket. CreateSpace Independent Publishing Platform, 2016.
*	Sklar, David Learning PHP 5 O’Reilly, 2004. GitHub Guides at https://guides.github.com, including: “Understanding the GitHub Flow”, “Hello World”, and “Getting Started with GitHub Pages”.
*	Jacobson, Daniel APIs: A Strategy Guide O’Reilly: 2012.
*	London, Kyle Developing Large Web Applications: Producing Code That Can Grow and Thrive O’Reilly, 2010.


### Assessment

Take home exam (50%) and in-class assessment (50%). Students will be expected to produce 10 problem sets in the MT. Student problem sets will be marked each week, and will provide 50% of the mark.

### Schedule

---
#### Week 1. What is Computation?

In the first week, we will introduce the basic concepts in computer programming: computers, algorithms, programming languages, and programs. We will then discuss the elements of programming languages: primitive constructs, syntax, static semantics, and semantics. We will further introduce the essential primitives for all programming languages: data types, operators, expressions, variables and values.

*Readings*:

* Guttag. Chapters 1-2.1, pp.1–15.
* Wing, Jeannette M. (2006). [Computational thinking](http://tech-insider.org/academia/research/acrobat/0603.pdf). *Communications of the ACM*, 49(3), 33–35.

*Lab*: **Anaconda, Jupyter, and GitHub**

* Installing Python with Anaconda
* Introduction to Jupyter and other IDEs
* Submitting assignments on GitHub

---
#### Week 2. Data Types in Python

In the next five weeks of the course, we will use Python to get familiar with the elements of programming languages. We will begin with scalar data types, operators, expressions, and value assignment to variables. We will also cover non-scalar, also known as compound or structured, data types (lists, tuples, sets, and dictionaries) and discuss the difference between mutable and immutable and ordered and unordered types. As lists are very commonly used, we will further overview the most common list operations, including indexing, slicing, appending, splitting, aliasing, and cloning.  

*Readings*:
* Guttag. Chapters 2.3, 5.1-5.3, 5.5-5.6, pp.18–21, 65–73, 77–84.

*Lab*: **Working with Strings and Lists in Python**
* Programing with simple statements, including `print()`, `len()`, `append()`, `extend()`, `pop()`, `remove()`, `split()`, `join()`, `sort()`, and `sorted()`

---
#### Week 3. Control Flow in Python

Control flow defines the order in which statements are evaluated and executed in a program. In Python, indentation plays a crucial role in determining the control flow. In this week, we will discuss branching and iteration and how to write these in Python using `if`-`else` statements, `while` loops, `for` loops, `range()`, `break`, and `continue`. We will also introduce the extremely useful concept of list comprehensions.

*Readings*:
* Guttag. Chapters 2.2, 2.4–3.2, pp.15–18, 22–30.

*Lab*: **For Loops and List Comprehensions in Python**
* Control flow best practices and pitfalls
* Nested dictionary and list comprehensions

---
#### Week 4. Functions in Python

Good programmers are not measured by the amount of code they write but by the amount of functionality in their code. Good programming relies on abstraction and decomposition. Decomposition creates structure while abstraction helps hide details. Decomposition and abstraction can be achieved with functions and classes and in this week, we will introduce functions. We will discuss function arguments and variable scope and by means of an example, we will introduce the concept of recursion.

*Readings*:
* Guttag. Chapter 4, pp.39–63.

*Lab*: **Writing and Calling Functions in Python**

---
#### Week 5. Classes in Python

Object-oriented programming is a programming paradigm that helps increase modularity, reduce complexity, and foster code reuse. Objects are a data abstraction consisting of (1) an internal representation i.e. object attributes and (2) an interface for interacting with the objects through methods and functions. Objects are instances of classes and classes determine the type of an object. In this week, we will discuss how to define classes in Python and how to create instances of a class. We will also touch upon class inheritance and hierarchies.

*Readings*:
* Guttag. Chapter 8, pp.109–134.

*Lab*: **Programming in Teams**
* Programming in teams
* Commenting code

---
#### Week 7. Testing and Debugging in Python

Writing computer programs is easy but making them work properly is hard. We test programs to check if they work as intended and we debug them when we find out that they don’t. In this lecture, we will discuss different ways to test and debug programs. We will cover common error messages and how to catch them with `try`, `except`, `raise`, and `assert`.

*Readings*:
* Guttag. Chapters 6–7, pp.85–108.

*Lab*: **Exceptions and Assertions in Python**

---
#### Week 8. Data Types and Control Flow in R

In the next two weeks of the course, we will review the concepts learned until now by learning how they are implemented in the R programming language. We will start with basic data types in R (vectors, lists, matrices, factors, data frames) and control flow (if-else statements, for and while loops, repeat, next, break).

*Readings*:

*Lab*: **Introduction to R**
* Installing R with Anaconda
* Introduction to RStudio and workflow
* Practicing simple statements and control flow

---
#### Week 9. Functions and Debugging in R

Continuing from the previous week, we will cover vectorized operations in R (including `lapply`, `mapply`, `tapply`, `split`), functions, and variable scoping.

*Readings*:


*Lab*: **Writing Functions in R**

---
#### Week 10. Algorithms and Order of Growth

Algorithms are recipes that consist of a sequence of simple steps, control flow, and stopping rule. To evaluate the scalability of algorithms and to compare their efficiency, we use the abstraction “order of growth”. Order of growth expresses how the maximum amount of time needed grows as the size of the input grows. We will discuss different complexity classes and ways to analyze the complexity of programs.

*Readings*:
* Guttag. Chapter 9, pp.135–149.

*Lab*: **Order of Growth**
* Reading and evaluating order of growth of programs written in Python and R

---
#### Week 11. Searching and Sorting Algorithms

We will use the concepts and approaches introduced in the previous lecture to look at the complexity of several classic algorithms on searching and sorting. The goal is to get a better intuition of how to approach problems of efficiency. We will use examples written in both Python and R. The lecture will end with an overview of Python modules and R packages that are useful for data manipulation, analysis, and visualization.  

*Readings*:
* Guttag. Chapter 10.1–10.2, pp.151–164.

*Lab*: **Course Summary**
* Writing programs in Python and R
* Useful libraries for data science
