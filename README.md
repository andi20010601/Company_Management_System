# Company_Management_System
With the advent of the information age, information management system in life plays an increasingly important role, it can make enterprises in a more effective and convenient way to complete functional work, so that it can work more quickly is possible, so we believe that the application of this system is very large and adapt to the needs of the development of the times, so this system is interesting. Once the system is designed, we believe that many offices will use it for efficient office purposes. For example, some after-school tutoring organizations can use this site to facilitate teachers, students to evaluate and submit assignments more efficiently, and software development companies and others can use this site to quickly transfer tasks between project managers and engineers.
The requirement of this project.

DS 2003	Fundamentals of Database Systems &
DS 2013 Data Processing Workshop I 
Course Project 
1.Introduction
In this project, you are supposed to model, design and implement a real world web application that is related to data analysis and database management. For example, a simple music management system, a university course arrangement system, a library book management system, an e-business inventory management system, a train ticket booking system, etc. (you are encouraged to propose your own application, innovative ideas will be given bonus points).  You should do the implementation using Python, Django framework and MySQL DBMS. Your web application should provide users reasonable operations based on your application and problem.

This is a group based project. Each group has 4 students. and you should choose your group via the grouping link on iSpace. You can come up with your proposals, but each topic can be chosen by at most 3 groups, we will inform you to change your topic if you are not the first three ones who picked the same topic within 3 days after you submitted your proposal.

2.Workflow Stages
The project workflow goes through several stages described below.
1.Problem definition. Each group will need to select a topic and formulate the problem, e.g., music management, e-business inventory management or ticket booking, etc.
2.Data collection. Each group will need to collect the data using the web scraping techniques introduced in DS 2013 Data Processing Workshop I.
a.Note: You can also download existing datasets or generate synthetic datasets if necessary. However, at least some information are crawled by yourself.
3.Wrangle, prepare, cleanse the data. The collected data may contains missing and noisy entries or in consistency schemas. Therefore, you need to perform data preprocessing and data cleaning.
4.Data analysis and visualization. Analyze, identify patterns, and explore the data use data analysis and visualization methods introduced in DS 2013 Data Processing Workshop I.
5.Database design. Design the database using the ER Model by creating an ER diagram and later on converting it into relations in MySQL DBMS.
6.Web development. Design and implement the website that provides a user interface to manage the database, including but not limited to query the database, insert/update/delete some records in database relations. 
Note: 
For DS 2013 Data Processing Workshop I course, assessment will focus on steps 2,3,4.
For DS 2003 Fundamentals of Database Systems course, assessment will focus on steps 1,5,6.

This project is aimed to help students to learn how to formulate a simple database-related problem/task/application and to gain hands on experience on how to solve the problem by using methods, algorithms and techniques taught in class. The students will conduct a project on an interesting application and will present the obtained results. Students are encouraged to identify new problems/tasks/applications.  

3.Assessment of Course Project (Total: 100% + 10%bonus)
Proposal 10% 
Correctness and completeness (in data analysis, database design, system implementation, and functionalities) 50% 
Documentations (reasonable assumptions and justifications.) 10% 
Presentation (Organize ideas into clearly identifiable sections with all information presented in logical sequence) 10% 
Demonstration (clarity and smoothness of the demo) 20% 
Bonus (outstanding or innovative features in addition to the implementation of correct and complete fundamental functions) maximum 10% 
4.Project Proposal (Due on May. 10th)
You should submit a two or three pages document to propose the application you are going to work on. The proposal should try to answer the following questions:
What is the problem you are solving?
Why is it interesting and who would use it when solved?
What are the functional requirements of your application?
What work do you plan to do in the project? 
What is the ER diagram? You need to have no less than 6 entities and 5 relationships in your ER diagram.
What assumptions do you make?
How will you measure success? How do you test your application to make sure the functional requirements are all implemented properly?
What do you expect to submit/accomplish by the end of the semester?

5.Requirements
a)Deliverables:
1.All code for your application, including the web scraping code, data preprocessing and analysis code, database code  (.sql ) and web development code.
2.Any auxiliary files needed by your program to create the database(e.g., .xml, .txt, etc).
3.The documentation of the whole project (.doc or .docx).
All the files should be named as dbws_project_GroupXX_projectname_mXXXXXXX.extension, where .extension is the extension name of your file

b)UI requirement:
Your website needs at least 5 pages, each page need to include navigation bars, logo, footers, etc. 
Your website should allow user registration and login. At least two user types should be offered. For example, suppose you are building a bookstore website, your user types could be administrator, registered user and anonymous visitor.
Your website needs to include at least four features. The more features you have, the higher score you will earn. Feature is a workflow that can allow the user to perform a complete task. Take the example of bookstore, the features could be:
oA user searches books.
oAn admin adds new books.
oAn admin views purchasing history and statistical/analysis results.
o…

c)Record requirement:
On average, each table must have no less than 5,000 records. There is at least one table that has more than 50,000 records.

d)Performance requirement:
It takes less than 1 second to insert a record.
It takes less than 2 seconds to delete or search a record.
You may have to create an index to accelerate delete or search.

e)Project Documentation requirement:
1.Project description (e.g., background, purpose, functionalities, etc.)
2.Data description and data collection.
3.Data preprocessing and data analysis.
4.Latest version of ER diagram.
5.Assumptions you made.
6.Functional dependencies.
7.The SQL codes and the explanations.
8.Website design and feature implementation.
9.Difficulties you encountered when doing the project and how you handle them.
