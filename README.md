# LIBU

[![N|Solid](https://github.com/livelifedev/team-cool/blob/master/app/assets/images/logo.png?raw=true)](http://lib-u.herokuapp.com/)
# CONTENTS
- [Description](#Description)
- [Purpose](#Purpose-of-Libu-application)
- [Section 1. LIBU Application](#Libu-application)
    - [Functionality/Features](#Functionality-Features)
    - [Images](#Screenshots)
    - [Tech Stacks](#tech-stacks)
- [Design Documentation](#Design-documentation)
    - [Design Process](#design-process)
    - [User stories](#User-stories)
    - [User workflow diagram](#A-workflow-diagram-of-the-user-journey)
    - [Wireframe](#Wireframes)
    - [Database Entity Relationship Diagram](#Database-Entity-Relationship-Diagrams)
    - [Planning Process](#Details-of-planning-process)
    - [Project Timeline](#Project-plan-timeline)
    - [Screenshots of Trello board](#Screenshots-of-Trello-board)
- [Section 2. Short Answers](Section-2-Short-Answer-questions)

## Description
LIBU is a web application which students and teachers have access to and be able to easily find academic materials, on a wide range of subjects, without infringing on copyright laws. 

View our application, [please click here](https://lib-u.herokuapp.com/).
View our repo [here](https://github.com/livelifedev/team-cool)

## Purpose of LIBU application 
The aim is to provide a platform for students and teachers to upload, share and download academic materials created by their peers. This allows for materials to be covered under [Creative Commons](https://creativecommons.org/) licensing and can be distributed and shared freely.

In addition, LIBU is to become a community where students can share and discuss ideas with their peers and/or educators. The interface should make it easier for our users to locate relevant information by being intuitive, easy to navigate and grouping materials by subject.

# Section 1. LIBU APPLICATION
## Functionality / features
(i) Search educational materials based on different subjects: Mathematics, History, Science, Geography, English and Biology
(ii) Create and upload new academic materials to share with other members
(iii) Bookmarks users' favorite documents
(iv) Ratings
(v) Comments

## Screenshots
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/homepage_view.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/homepage2.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/subjects.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/upload_create.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/user_dashboard.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/user_profile.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/search.png?raw=true)
## Tech stack (e.g. html, css, deployment platform, etc)
(i) Ruby on Rails
(ii) HTML
(iii) CSS and SASS for styling
(iv) Stripe for payment
(v) Devise for users
(vi) Cypress for application testing
(viii) Github for collaboration
(ix) GitKraken for collaboration
(x) Trello for project management
(xi) Slack for communication
(xii) Lucidchart for ERD
(xiii) Bootstraps for styling
(xiv) Faker gems to generate random data
(xv) Ransack for search functions
(xvi) TZInfo-Data for setting timezone database
(xvii) CanCan for user authorization
(xviii) Heroku for deployment
(xix) AWS

## Design documentation

#### Design process
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/workflow.png?raw=true)
#### User stories
(i) As a student with minimal income, I want to be able to quickly access to a low cost and up-to-date research in European history as I’m completing my final year in Bachelor of Arts.
(ii) As a year 12 student, I’d love to access other students’ works in Mathematics on my phone so I could be better prepared for my HSC at the end of this year
(iii) As a teacher, I would like to share my research materials and books in a platform for academics
#### A workflow diagram of the user journey/s.
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/user_flowchart.png?raw=true)
#### Wireframes
View our wireframe documents [here](https://drive.google.com/file/d/1VY1LZgJODxal_xDovEaXdbKk0HLO-Ys6/view?usp=sharing)
#### Database Entity Relationship Diagrams
![N|Solid](https://files.slack.com/files-pri/TFS42BWG0-FJMEPG9HV/erd_final.jpeg)
#### Details of planning process
(i) Initial Planning, Research & Brainstorming
(ii) Design Process, Wireframing & ERD
(iii) Approval for Concepts, Wireframing & ERD
(iv) Work on application and styling
(v) Finalize all features and styling
(vi) Documentations
(vii) Project Completion - Presentation
#### Project plan & timeline
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/Timeline.png?raw=true)
#### Screenshots of Trello board(s)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/trello.png?raw=true)
## Section 2. Short Answer questions 

##### 1. What is the need (i.e. challenge) that you will be addressing in your project?
    
For students and teachers to have access to and be able to easily find academic materials, on a wide range of subjects, without infringing on copyright laws. 


##### 2. Identify the problem you’re trying to solve by building this particular marketplace App? Why is it a problem that needs solving?
Students have to learn a lot, a broad amount of topics across many different topics. It can be overwhelming and time-consuming filtering search results in search engines for concise and relevant information.

Sometimes it is also difficult to understand some of the material that you find online, some of it is just vague writing that briefly addresses multiple topics just to have a quick internet article. 
Both teachers and students have quality knowledge that can be useful to others, so having a central place where teachers and students can share and publish quality and relevant articles and materials is the challenge that we are addressing.

##### 3. Describe the project will you be conducting and how. your App will address the needs.

We aim to develop a platform for students and teachers to upload, share and download academic materials created by their peers. This allows for materials to be covered under creative commons licensing and can be distributed and shared freely. 
It also aims to be a space where students can share and discuss ideas with their peers or educators. 
The interface should make it easier for the user to locate relevant information by being intuitive, easy to navigate and grouping materials together by subject. 


##### 4. Describe the network infrastructure the App may be based on.
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/networ_infrastructure.png?raw=true)

##### 5. Identify and describe the software to be used in the App.
The full list of softwares and applications used in developing our application is listed in our [tech stacks](#tech-stacks)
(i) Ruby on Rails: Rails is a model–view–controller (MVC) framework, providing default structures for a database, a web service, and web pages. It encourages and facilitates the use of web standards such as JSON or XML for data transfer, HTML, CSS and JavaScript for user interfacing. In addition to MVC, Rails emphasizes the use of other well-known software engineering patterns and paradigms, including convention over configuration, don't repeat yourself (DRY), and the active record pattern.
(ii) HTML: the standard markup language for creating our web application.
(iii) CSS: style sheet language used for describing the presentation of our application.
(iv) Cypress: testing application which we use to test our front-end
(v) Other third-party applications used in our app are: Devise for managing users, Stripe for processing subscription payments, Heroku for application deployment, GitKraken for collaboration, Slack for constant communication among team members, Trello for planning and tracking development process
##### 6. Identify the database to be used in your App and provide a justification for your choice.
PostgreSQL is used for this rails app, it is a free open source and community driven database management system that contain all the necessary features for managing general purpose object-relational databases, plus it is easy to install on the OS, it’s compatible and easy to setup with Rails and there is wide range of support and documentation online.

##### 7. Production database setup (i.e. postgres instance).
For our LIBU application, we use Heroku to create a Postgresql Database Instance. Heroku will create a name for our application when we run $ git push heroku master. Once it is created, we migrate our database on to Heroku by running $ heroku run rails db:migrate.

##### 8. Architecture of the App.
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/app_architecture.png?raw=true)
##### 9. Explain the different high-level components (abstractions) in the App.
Abstraction is divided into 3 different levels: physical, logical and view level.
(i) Physical abstration is the lowest level of abstraction which describes how our system actually stores data.
(ii) Logical abstraction is to describes what data our database stores, and what relationships exist among those data. 
(iii) View abstraction: it is the highest level of abstraction which describes only part of the entire database. Users of our database system do not need every single information; instead, they need to access only a part of the database. The view level of abstraction exists to simplify their interaction with the system. The system may provide many views for the same database.

##### 10. Detail any third party services that your App will use.

Stripe for payment processing
Cypress for application testing
Devise for user registration
Heroku for application deployment

##### 11. Describe (in general terms) the data structure of marketplace apps that are similar to your own (e.g. eBay, Airbnb). 
Bored of Studies - http://www.boredofstudies.org/ 
Bored of studies is a platform for students within NSW and VIC to share their essays from year 11 and 12 HSC with other members of the site. 
Each resource has an associated; description, subject, title etc. and these can be used to search database.

##### 12. Discuss the database relations to be implemented.
Most of the database relationships concern the one-to-many type of relationship, these include the users to listings, users to questions, users to bookmarks, users to comments, users to ratings. These are all one-to-many relationships, in that the user can have many of each of these elements, but the elements themselves can only belong to one user.
The same is true for questions to answers. We can have multiple answers for one questions, but those answers can only belong to the one question.
The other relationship that we have in our databases is the many-to-many relationship, this is for listings to subjects. A listing can have multiple subjects and a subject can belong to multiple listings.
Databases can also reference (establish a relationship) with more than one database, such as the ratings has the one-to-many relationship with both users and listings, because a user will create a rating on a listing so the rating will have both the user’s and listing’s id.

##### 13. Describe your project’s models in terms of the relationships (active record associations) they have with each other.
(i) User has many documents, bookmarks, comments, ratings, questions and answers
(ii) Subject has many documents through document-subjects
(iii) Rating belongs to users and documents
(iv) Question belongs to users and has many answers
(v) Document belongs to users, has many subjects through document-subjects, has many ratings, comments and bookmarks and has one attached document
(vi) Document-subject belongs to documents and subjects
(vii) Comment belongs to user and document
(viii) Bookmark belongs to user and document
(ix) Answer belongs to user and question

##### 14. Database schema design
![N|Solid](https://files.slack.com/files-pri/TFS42BWG0-FJMEPG9HV/erd_final.jpeg)

##### 15. User stories 
(i) As a student with minimal income, I want to be able to quickly access to a low cost and up-to-date research in European history as I'm completing my final year in Bachelor of Arts.
(ii) As a year 12 student, I'd love to access other students' works in Mathematics on my phone so I could be better prepared for my HSC at the end of this year
(iii) As a teacher, I would like to share my research materials and books in a platform for academics

##### 16. Wireframes for your App.
[Wireframing Documents](https://drive.google.com/file/d/1VY1LZgJODxal_xDovEaXdbKk0HLO-Ys6/view?usp=sharing) 

##### 17. How tasks are allocated and tracked in our project.

We split the project into front end and back end. 

We all had a shared [Trello board](https://drive.google.com/file/d/1zRKFKs49JYjieJaIxrs7cit-pkVIHi95/view?usp=sharing) which we posted tasks on.
 
We were always communicating via [Slack](https://drive.google.com/file/d/1SXJ2IFB9sQsaSef8Ryyna_Ddg2Dk7XTi/view?usp=sharing ) to keep each other updated about what was going on.


##### 18. Discuss how Agile methodology is being implemented in your project.
Step 1: Planning
* Brainstorming for ideas
* Gather information related to user stories
* Prepare initial design, allocate task and draft ERD

Step 2: Design
* Break down of task
* Map out all features and relationship diagram
* Determine high level components to be used such as Devise, Stripe, AWS, Heroku

Step 3: Execution
* Coding
* Automated Testing
* Iteration review after finishing every feature

Step 4: Finalization
* Launch to test the product on Heroku
* Review the app

##### 19. Provide an overview and description of your Source control process.
In term of source control, we use Git for tracking changes in source code during our application development.
(i) Starting with the basics: one Repo owner and all members branch out from master to work on different tasks
(ii) Keep our source code in Github and using GitKraken to track our progress
(iii) Ensure the working file is from the latest version of the source file.
(iv) Commit often 
(v) Make clear notes in the “add comments” about why the changes were made before pushing them to GitHub

##### 20. Provide an overview and description of your Testing process.
For testing, we use Cypress which is a Javascript-based end end-to-end testing framework. Cypress gives us the ability to take shortcuts and programmatically login feature before any tests run. That means we don’t have to visit a login page, type in an email and password, and run the test. 
We test number of features in our application: user’s registration, log in, update profile, creating documents and queries.
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/cypress_testing.png?raw=true)

In addition, we also conducted the following tests
(i) Usability Test Cases
* Web page content should be correct without any spelling or grammatical errors
* All fonts should be same throughout the application
* All the error messages should be correct without any spelling or grammatical errors and the error message should match with the field label.
* Enough space should be provided between field labels, columns, rows, and error messages.
* All the buttons should be in a standard format and size.
* Home link and navbar should be there on every single page.
* Confirmation message should be displayed for any kind of update and delete operation.
* Check the site on different resolutions (640 x 480, 600x800 etc.?)
* Check the end user can run the system without frustration.
* Check the navbar should work properly.
* Title should display on each web page

(ii) Functional Test Case:
* Test all the mandatory fields should be validated.
* Test the numeric fields should not accept the alphabets and proper error message should display.
* Test that a confirmation message should display for update and delete operations.
* Test the Privacy Policy is clearly defined and should be available for users.
* Test if any functionality fails the user gets redirected to the custom error page such as sign up and login functionality
* Test all the uploaded documents are opened properly.
* Test the user should be able to download the uploaded files.
* Test the app properly working in different browsers (IE, Firefox, Chrome, safari and Opera).

(iii) Test Cases for Database Testing:

* Verify the database name: The database name should match with the specifications.
* Verify the Tables, columns, column types and defaults: All things should match with the specifications.
* Verify the Primary and foreign key of each table.
* Test the stored procedure with sample input data.
* Verify the data gets properly saved into the database after the each page submission.
* Verify the data for the Update, delete and upload operations are performed.
* Verify the encrypted data in the database are appropriately saved and out of public view


##### 21. Discuss and analyse requirements related to information system security.
Information system security (ISS)  and protection of personal information need to be addressed and implemented right at the start of the development process. 
Ensure personal data stored on our server remain accessible and useful to only legitimate users.
Implement measures to protect the application against malicious attacks and prevent unauthorized access to database.
Put preventative measures to guard against unauthorized use 

##### 22. Discuss methods you will use to protect information and data.

Users can only access their own profile using their own passwords 
Restricting users privileges
Minimal error messages
Using validation on both front-end and back-end
Ensure correct file extension are uploaded

##### 23. Research what your legal obligations are in relation to handling user data.
In Australia, handling customer data and private information are regulated by the Australian Privacy Act (1988) which includes 13 Australian Privacy Principles (APPs). Its purpose is to promote transparency and accountability in information handling and require businesses to notify of any privacy and/or data breaches. 
Ensure LIBU manage personal information in an open and transparent way - providing our users to our Privacy policy 
LIBU can collect personal information that is requested and security measures are put in place to ensure the safety of personal sensitive information
Ensure users aware and understand when and in what circumstances that LIBU collect personal information
Advise users how we may use and disclose personal information that we holds
LIBU takes reasonable steps to protect personal information from misuse, interference and loss and from unauthorized access, modification or disclosure
LIBU has the obligation to provide when users request to access their own personal information and update them accordingly

