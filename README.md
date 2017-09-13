# ST445 Managing and Visualizing Data


### Michaelmas Term 2017

### Instructors

* [Kenneth Benoit](k.r.benoit@lse.ac.uk), Department of Methodology.  *Office hours*: By appointment, COL 8.11
* [Milan Vojnovic](M.Vojnovic@lse.ac.uk), Department of Statistics.  *Office hours*: TIME, BLDG

### Teaching Assistant 
* [Christine Yuen](L.T.Yuen@lse.ac.uk), Department of Statistics.  *Office hours*: Thursday 14:30 - 15:30, COL 5.01

### Course Information

* Lectures on Tuesdays 10:00–12:00 in CLM.2.02
* Classes on Thursdays 13:00–14:30 in TW2.4.02

No lectures or classes will take place during School Reading Week 6.


### Course Description

This course will cover the principles of digital methods for storing and structuring data, including data types, relational and non-relational database design, and query languages. Students will learn to build, populate, manipulate and query databases based on datasets relevant to their fields of interest. The course will also cover workflow management for typical data transformation and cleaning projects, frequently the starting point and most time-consuming part of any data science project. This course uses a project- based learning approach towards the study of online publishing and group -based collaboration, essential ingredients of modern data science projects. The coverage of data sharing will include key skills in on-line publishing, including the elements of web design, the technical elements of web technologies and web programming, as well as the use of revision- control and group collaboration tools such as GitHub. Each student will build one or more interactive website based on content relevant to his/her domain -related interests, and will use GitHub for accessing and submitting course materials and assignments.

A core objective of this course is to provide students with a well-rounded sense of "data science literacy", meaning you will become familiar with the core structures, terms, protocols, and software that forms the core material of data science and applied computing.  This is a broad category, covering abstract concepts such as database normal forms and complex data structures, but also covers a range of simple tools and formats such as markup languages, web publishing, and working with APIs (application programming interfaces).  In the second half of the course, we will focus on communicating results visually through turning data into plots and other visualizations.

On the theory side, introduce principles and applications of the electronic storage, structuring, manipulation, transformation, extraction, and dissemination of data. This includes data types, database design, data base implementation, and data analysis through structured queries. Through joining operations, we will also cover the challenges of data linkage and how to combine datasets from different sources. We begin by discussing concepts in fundamental data types, and how data is stored and recorded electronically. We will cover database design, especially relational databases, using substantive examples across a variety of fields. Students are introduced to SQL through MySQL, and programming assignments in this unit of the course will be designed to insure that students learn to create, populate and query an SQL database.  We will briefly compare relational databases to other formats of database manager, the "NoSQL" types such as MongoDB, including the JSON data format.  Students will be encouraged to work with data relevant to their own interests as they learn to create, populate and query data.

On the practical side, we will cover a variety of tools with which every data scientist should be familiar, including revision control tools, web publishing formats, tools and commands for reshaping and recasting data, how to work with different data formats, how to merge and link data, and how to publish a website.

In the data visualisation part of the course, we will...



### Organization

This course is an introduction to the fundamental concepts of data and data visualization for students and assumes no prior knowledge of these concepts.  

The course will involve 20 hours of lectures and 15 hours of computer workshops in the MT. 	


### Prerequisites

No prior experience with programming is required.


### Software

We will use some tools, notably SQLite, R, and Python, but these will be used in coordination with MY470 (Computer Programming) where their use will be covered more formally.  Lectures and assignments will be posted on Github, Students are expected to use Github also to submit problem sets and final exam.

Where appropriate, we will use Jupyter notebooks for lab assignments, demonstrations, and the course notes themselves.

### Materials

The main course texts will be:

*   Karumanchi, Narasimha.  _Data Structures and Algorithms Made Easy: Data Structure and Algorithmic Puzzles_, Second Edition.  5th ed.  CreateSpace Independent Publishing Platform, 2017.
*	Lee, Kent.  _Data Structures and Algorithms with Python_. Springer, 2015.
*	GitHub Guides at https://guides.github.com, including: "Understanding the GitHub Flow", "Hello World", and "Getting Started with GitHub Pages".

### Assessment

Take home exam (50%) and in-class assessment (50%). Students will be expected to produce 10 problem sets in the MT. Student problem sets will be marked each week, and will provide 50% of the mark.

### Schedule

---
#### Week 1. Introduction to Data and Data Types

In the first week, we will introduce the basic concepts of the course, including how data is recorded, stored, and shared.  Because the course relies fundamentally on GitHub, a collaborative code and data sharing platform, we will introduce the use of git and GitHub, using the lab session to guide students through in setting up an account and subscribing to the course organization and assignments.  

This week will also introduce basic data types, in a language agnostic manner, from the perspective of machine implementations through to high-level programming languages.  We will introduce the notion of databases and database managers, and the client-server model.

*Readings*:
* something from Karamanchi or the Lee text.
* Chacon, Scott and Ben Straub. [_Pro Git_](https://git-scm.com/book/en/v2). 2nd ed. Apress.  Chapters 1-2.
* [GitHub Guides](https://guides.github.com), especially: "Understanding the GitHub Flow", "Hello World", and "Getting Started with GitHub Pages".
* Jim McGlone, "[Creating and Hosting a Personal Site on GitHub
A step-by-step beginner's guide to creating a personal website and blog using Jekyll and hosting it for free using GitHub Pages.](http://jmcglone.com/guides/github-pages/)".

*Further Readings*:
* Nelson, Meghan.  2015.  "[An Intro to Git and GitHub for Beginners (Tutorial).](http://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)"


*Lab*: **Setting up a website using GitHub pages**, by forking a repository, staging and committing changes, and pushing these to a repository for publishing a website using Jekyll.
* Installing git and setting up an account on GitHub
* Using Jupyter notebooks on GitHub
* How to complete and submit assignments using GitHub Classroom
* Cloning a website repository, modifying it, and publishing a personal webpage

---
#### Week 2. Deciphering the languages of the Internet

This week covers markup languages, content style sheets, and web protocols for publishing and transmitting data.  Continuing from the material covered in the first week lab session, we will cover markup languages, including HTML, XML, and Markdown, as well as common data formats such as JSON (Javascript Object Notation).  We will learn about class abstraction using CSS (content style sheets) and adding functionality to web pages through the use of simple Javascript.  We will also cover the client-server model, and how machines and humans transmit data over networks and to and from databases.

*Readings*:
*   Severance, Charles Russell.  [_Introduction to Networking: How the Internet Works_](http://www.net-intro.com).  Charles Severance, 2015.
*	Duckett, Jon.  _HTML and CSS: Design and Build Websites_.  New York: Wiley, 2011.

*Further Resources*:
* GitHub.  "[Markdown Syntax](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)" (a cheatsheet).  
* Shay Howe. 2015.  [_Learn to Code HTML and CSS: Develop and Style Websites_](http://learn.shayhowe.com/html-css/).  New Riders.  


*Lab*: **Advanced on-line publishing**
* Mastering Markdown.
* Adding functionality to our website, and creating an interface to web data.

---
#### Week 3. Complex Data Types and Structured Data

This week moves beyond the rectangular format common in statistical datasets, modeled on a spreadsheet, to cover relational structures and database normalization.  We will also cover ways to restructure data from "wide" to "long" format, within strictly rectangular data structures.  We will also cover more complex data types found in programming languages, including user-defined data types, using Python and R structures as examples.

*Readings*:
* Lee, Kent.  _Data Structures and Algorithms with Python_. Springer, 2015.

*Further Resources*:
* The [**reshape2** package](http://had.co.nz/reshape/) for R.
* Reshaping data in Python: "[Reshaping and Pivot Tables](https://pandas.pydata.org/pandas-docs/stable/reshaping.html)".  
* Robin Linderborg, "[Reshaping Data in Python](https://hackernoon.com/reshaping-data-in-python-fa27dda2ff77)", 20 Jan 2017.

*Lab*: **Reshaping and normalizing data**
* Moving from wide to long data and back again, in R and Python.
* Merge and join operations.
* Using lookup and "hash" tables.
* Normalizing tables through key relations.

---
#### Week 4. Creating and managing databases

We will return to database normalization, and how to implement this using good practice in a relational database manager, SQLLite.  We will cover how to structure data, verify data types, set conditions for data integrity, and perform complex queries to extract data from the database.  We will also cover authentication and how to connect to local and remote databases.   Finally, for a comparison, we will show a different (non-relational) database model through MongoDB, contrasting this to the relational paradigm.

*Readings*:
*	Lake, Peter.  _Concise Guide to Databases: A Practical Introduction_. Springer, 2013.
*	Nield, Thomas. _Getting Started with SQL: A hands-on approach for beginners_. O’Reilly, 2016.

*Further Resources*:
* [SQLite documentation](https://www.sqlite.org/docs.html).
*   Bassett, L. 2015.  [_Introduction to JavaScript Object Notation: A to-the-point Guide to JSON_](http://shop.oreilly.com/product/0636920041597.do).  O'Reilly Media, Inc.

*Lab*: **Working with a relational database manager**
* Normalizing a data structure and storing it in SQLLite
* Enforcing data integrity
* Constructing queries


---
#### Week 5. Working with text and other published data

Publicly accessible _application programming interfaces_ (APIs) provide a common source of "big" data available from a variety of sources, such as social media data.  This data consists of a variety of data types, but is usually transmitted in JSON format.  In this session, we will cover the basics of APIs, including authentication and the use of protocols for interacting with APIs, and in processing the data that is obtained using these methods.  We will also discuss common problems in using text, including character encodings, working with Unicode, transforming text into numeric data, and cleaning textual data for analysis.

*Readings*:
*   something on text, TBC
*   Cooksey, Brian.  _An Introduction to APIs_.  Zapier, 2014.


*Further Resources*:
* [Documentation on the Twitter REST API](https://dev.twitter.com/rest/public)
* Richard Ishida. 2015.  "[Character encodings for beginners](https://www.w3.org/International/questions/qa-what-is-encoding)".  W3C.

*Lab*: **Working with social media data: Twitter**
* Download Twitter data using Twitter's REST APIs
* Clean and process the data
* Normalize the data and store it
* Perform basic analysis of the text and non-textual data.


---
#### Week 6. Reading Week


---
#### Week 7. Data Visualisation 1

Description here.

*Readings*:
* Readings here

*Lab*: **Lab Title Here**
* lab details 1
* lab details 2

---
#### Week 8. Data Visualisation 2

Description here.

*Readings*:
* Readings here

*Lab*: **Lab Title Here**
* lab details 1
* lab details 2

---
#### Week 9. Data Visualisation 3

Description here.

*Readings*:
* Readings here

*Lab*: **Lab Title Here**
* lab details 1
* lab details 2

---
#### Week 10. Data Visualisation 4

Description here.

*Readings*:
* Readings here

*Lab*: **Lab Title Here**
* lab details 1
* lab details 2

---
#### Week 11. Data Visualisation 5

Description here.

*Readings*:
* Readings here

*Lab*: **Lab Title Here**
* lab details 1
* lab details 2
