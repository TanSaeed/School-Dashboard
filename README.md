# .Net MVC 5 School Dashboard 
This web app is designed to allow a teacher to make a test for the students in the class. The students can register and take the tests. A super admin initially creates the teacher accounts. This application was made using .Net and MVC 5 controller. The teacher can make custom tests and questions. The questions are indexed into a database and randomly picked from and used in the test. The test is 10 questions long. The teacher can make multiple tests. The student signs up and takes the tests available for them with a grade being shown at the end of the test. The super admin can do all the teacher does but is also allowed to make teacher accounts and only really exists to maintain the database and add teachers. 

## Installation

To install Visual Studio is required, should work with everything after Visual Studio 2015. To run clone the repository, and run Asp.net MVC TestpreparationAppDemo.sln. Once loaded into Visual Studio run IIS Express. 

## Technologies

- Visual Studio: HTML, CSS, JavaScript, C#.
- Hosting: Azure.
- Programing Paradigm: Agile SCRUM methodology with a team, MV 5 Controller.

## Features

- Teacher can make tests
- Teacher can add questions to test
- Test is randomized and can be taken by anyone
- Questions and answers are calculated
- Score is shown at the end
- Students can register
- Data for questions, tests, and users are stored in the database

## Documanttion 

#### Authorization: Anonymous, User(student), User(teacher), and Super admin

#### Premade Accounts in Database

- Superadmin; User=Super@Admin.com  , Password=!Aa123
- Teacher;    User=FDR@Prof.com     , Password=321
- Student;    User=Jimmy@Student.com , Password=123
