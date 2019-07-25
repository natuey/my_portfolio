[![N|Solid](https://foodladder.org/wp-content/uploads/2018/08/bannerlogo.png)](http://food-ladder-bucket.s3-website-ap-southeast-2.amazonaws.com/)

# CONTENTS

- [Assessment Description](#Assessment-Description)
- [Client Description](#Client-Description)
- [Purpose](#Purpose-of-Food-Ladder-Web-application)
- [Food Ladder Application](#Food-Ladder-application)
  - [Deployment Instructions](#Deployment-Instructions)
  - [Version Control Process](#Version-Control-Process)
  - [Functionality/Features](#Functionality-and-Features)
  - [Images](#Screenshots)
  - [Tech Stacks](#tech-stacks)
- [Design Documentation](#Design-documentation)
  - [Design Process](#design-process)
  - [User stories](#User-stories)
  - [User workflow diagram](#User-Workflow-Diagram)
  - [Wireframes](#Wireframes)
  - [Database Diagram](#Database-Diagram)
  - [Planning Process](#Details-of-planning-process)
  - [Project Timeline](#Project-plan)
  - [Screenshots of Trello board](#Screenshots-of-Trello-board)
- [Short Answers](#Short-Answer-Questions)

## Assessment Description

We are to design, build, deploy and present a web application (App) built for a real world customer.

Find a business or organisation (preferably near your campus) to build an App for.

Meet with the business owner or organisation manager to find out what challenges they face. Find a problem that you can solve with an App and present your ideas to the client.

## Client Description

Food Ladder is committed to leading the implementation of innovative and sustainable technologies to in-need communities and works exclusively with a host of world-class, tailored and proven products. As Food Ladder expands to other communities around the world, it would like to develop a web application to enhance its communications. So rather than having human resources in each country (which comes at an immense cost), Food Ladder can support communities virtually.

How it would work is communities implement basic greenhouses structures using our blueprint and recommended supplier. We will then provide the know-how and support via manuals (operating guides, education, curriculums etc) and an online platform (website and app) so the system can thrive. This online platform will not only be a tool for communities to speak to our horticulture experts it will also be a self-moderating virtual community, where communities around the world can assist one another, providing growing tips, class ideas etc.

View Food Ladder live web application, [HERE](http://food-ladder-bucket.s3-website-ap-southeast-2.amazonaws.com/)<br/><br/>
View our Github repos here for:

- [BACK-END](https://github.com/bHarlum/food-ladder-express)
- [FRONT-END](https://github.com/bHarlum/food-ladder-react) <br/><br/>

Project-related documentations

- [Web Development Brief](https://drive.google.com/file/d/1MDe6ay3fjost7yoTT3l4NNSvtFWNS0JR/view?usp=sharing)
- [Statement of Work](https://drive.google.com/file/d/1Ns3DQnt1MW6LGi3ZTkj1bmLtNpVW6UpA/view?usp=sharing)
- [Client Communication Tracker](https://drive.google.com/file/d/1ta32D3-DIKY0L-dYFf9eZsezriMuvh8O/view?usp=sharing)
- [Client Satisfaction Survey](https://www.surveymonkey.com/r/PDB6MRC)

## Purpose of Food Ladder Web Application

To extend Food Ladder's reach by focusing on what they do best, creating social enterprises. Communities or schools will implement basic greenhouse structures, which they pay for, build and maintain. Food Ladder then provide the know-how and support via manuals and an online platform, so the system can thrive.

This online platform will not only be a tool for communities to speak to Food Ladder's horticulture experts it will also be a self-moderating virtual community, where communities around the world can assist one another, providing growing tips, class ideas etc. Food Ladder believe this online solution will thrive in developing countries, with the World Bank finding the poorest households are more likely to have access to mobile phones than to toilets or clean water.

## FOOD LADDER APPLICATION

## Instructions:

Cloning the project and installing Dependencies. Ensure you run 2 terminal windows, one for express (back-end) and one for front-end.

###### Back-end:

-       $ git clone https://github.com/bHarlum/food-ladder-express.git
-        $ cd food-ladder-express
-        $ npm install
-        $ npm run dev-server

###### Front-end:

-       $ git clone https://github.com/bHarlum/food-ladder-react.git
-       $ cd food-ladder-react
-       $ npm install
-       $ npm start

###### Other requirements:

- MongoDB
- AWS

## Deployment Instructions

View our [Deployment Instructions](https://docs.google.com/document/d/1rIXq4x8JuGYdHgKocJmVhcpoPfdOB3HAkWXFK0atJ38/edit?usp=sharing)

## Version Control Process

###### The Food Ladder project was split into three different types of branches:

- The master branch was only reserved for tested working code. All code that is pushed to here should have been at least manually tested and not have any errors.

- The dev branch is reserved for the merging of feature branches, testing that they work and bringing them together with other features.

- The feature branches were where each feature was developed. Each branch had an informative name that related to the work being done. Once the required work was completed, a pull request would be generated and another team member would be assigned to review the code.

###### Reviewing:

Whenever a request to merge is made from a feature branch into dev, a team member would review each file that had changes and ensure that convention and correct coding practice was being followed.
If small changes are required, a comment should be left by the reviewer and the pull request left without being merged. The comment should addressed through changes to the code or communication. Once any issues have been revolved, the pull request can be accepted and merged.
Large changes will mean that the request should be rejected, and comments made to suggest changes.

###### Tools:

Github: Host for the project repo.
Gitkraken: Used by all members to provide a GUI for interacting, viewing and making changes to branches, managing the project as a whole.

## Functionality and features

#### CORE GOALS

##### ‘Invitation code only’ registration:

- Communities will be sent a unique invitation code before registration is available to them.

##### Community Forum

- Questions and informative posts will be grouped by topic.
- Tags will be automatically added based on keywords from
  content.
- Multilingual functionality
- Admin/expert account posts and responses will
  behighlighted.
- Search functionality

##### Monthly Reporting from Members

- Metrics to be tracked over time.
- Notifications when reports are due.
- Online community only available to users if they submit
  their monthly reports.
- Functionality will be scaled down in this version of the
  application.

##### FAQ Section

##### Directory of Help Guides, Manuals & Blueprints for users

##### Document/Image/Video Upload

- Storage through Amazon Web Services.
- File size limit
- Automatic video compression and clearing of older files

##### Admin Capabilities

- Access to user data and metrics
- Ability to download and save documents/images/videos

## Screenshots

![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/app_landing.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/login.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/app_project_dashboard.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/app_new_project.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/forum_page.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/app_comments.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/app_resources.png?raw=true)

## Tech stacks

#### CORE STACKS: MongoDB, Express, React and NodeJS

##### EXPRESS

FOREVER: CLI tool for ensuring that a given script runs continuously.

NODEMON: a tool that helps develop node.js based applications by automatically restarting the node application when file changes in the directory are detected.

BCRYPTJS: hash passwords

CELEBRATE: celebrate is an express middleware function that wraps the joi validation library. This allows you to use this middleware in any single route, or globally, and ensure that all of your inputs are correct before any handler function.

CORS: a node.js package for providing a Connect/Express middleware that can be used to enable CORS with various options.

DOTENV: Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env

JSONWEBTOKEN: way for securely transmitting information between parties as a JSON object. ... Signed tokens can verify the integrity of the claims contained within it, while encrypted tokens hide those claims from other parties.

MAILGEN: A Node.js package that generates clean, responsive HTML e-mails for sending transactional mail.

MONGOOSE: Mongoose is a MongoDB object modeling tool designed to work in an asynchronous environment.

MORGAN: HTTP request logger middleware for node.js

PASSPORT: Passport is Express-compatible authentication middleware for Node.js. Passport's sole purpose is to authenticate requests, which it does through an extensible set of plugins known as strategies. Passport does not mount routes or assume any particular database schema, which maximizes flexibility and allows application-level decisions to be made by the developer. The API is simple: you provide Passport a request to authenticate, and Passport provides hooks for controlling what occurs when authentication succeeds or fails.

PASSPORT-JWT: A Passport strategy for authenticating with a JSON Web Token. This module lets you authenticate endpoints using a JSON web token. It is intended to be used to secure RESTful endpoints without sessions.

PASSPORT-LOCAL: Passport strategy for authenticating with a username and password. This module lets you authenticate using a username and password in your Node.js applications. By plugging into Passport, local authentication can be easily and unobtrusively integrated into any application or framework that supports Connect-style middleware, including Express.

PASSPORT-LOCAL-MONGOOSE: Passport-Local Mongoose is a Mongoose plugin that simplifies building username and password login with Passport.

VALIDATOR: A library of string validators and sanitizers.

##### REACT

REACT-REDUX : binding React with Redux

REDUX : Tool for State Management. Reasons: a single store is used to keep the state of the app
REDUX-FORM: way to manage your form state in Redux.

REDUX-THUNK: Redux Thunk middleware allows you to write action creators that return a function instead of an action. The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met.

ANT-DESIGN: design creation. Reasons: it provides components, resources and tools for process optimization.

JEST: Javascript Testing solution. Reasons: Tests are created by developers with snapshot is created automatically. If there are differences between tests (ie. snapshots), developers get notified the changes.

## Design documentation

#### Design process

![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/workflow.png?raw=true)

#### User stories

(i) As a Project member, I want to be able to post any issues I have with the project to gather answers and support.<br/>
(ii) As a staff member, I want to be able to create a new project and generate a unique invitation code to send to a community member.<br/>
(iii) A a project member, I want to be able to search existing posts to see if my problems have been solved in the past.<br/>
(iv) As a project member, I want to easily conduct monthly reporting to maintain FoodLadder's ongoing support to my project.<br/>
(v) As a staff member, I want to reduce on site presence to reduce costs.<br/>
(vi) As a staff member, I want to be notified of new queries from our members in order to provide them prompt replies.<br/>
(vii) As a staff member, I want an easy-to-use online community so project members can easily access support.<br/>
(viii) As a project admin, I would like to be able to sign up easily and enter my project's details.<br/>
(ix) As a team member, I would like to access the community in my preferred language.<br/>
(x) As a project admin, I want to be able to give members of my community access to online services.<br/>
(xi) As a staff member, I want to be able to invite projects to join our online community.<br/>
(xii) As a staff member, I want to navigate easily on the website so I could work remotely.<br/>
(xiii) As a team member, I want to see what other projects are discussing on the community forum.<br/>
(xiv) As a staff member, I want to be notified about activity on monthly project reports.<br/>
(xv) As a project admin, I want to be able to see my report history as a snapshot.<br/>

#### User Workflow Diagram

![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/admin_flow.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/user_flow.png?raw=true)

#### Wireframes

View our entire wireframe documents [here](https://drive.google.com/file/d/1Hi-p0L60FumElySOaPAIwwcj_y67mols/view?usp=sharing)

![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/whiteboard-wireframes-01.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/landing_page.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/user_dash.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/project_rego.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/project_dashboard.png?raw=true)

#### Database Diagram

![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/Food%20Ladder%20-%20Database%20Diagram.png?raw=true)

#### Details of planning process

(i) Initial Planning, Research & Brainstorming<br/>
(ii) Design Process and Wireframing<br/>
(iii) Approval for Project Brief from Client<br/>
(iv) Work on application ( back-end and front-end)<br/>
(v) Finalize all features and styling<br/>
(vi) Documentations<br/>
(vii) Project Completion - Presentation<br/>

#### Project plan

![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/timeline.png?raw=true)

#### Screenshots of Trello board

![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/trello-tasks.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/client_meeting.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/stacks.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/users_stories.png?raw=true)

## Short Answer Questions

##### 1. What are the most important aspects of quality software?

In our opinion, the most important aspects of software quality are broken down to 3 areas: functional quality, structural quality, and process quality.

(i) Functional quality means that our application correctly performs the tasks and functionalities it’s intended to do for our client. For example:

- Meeting the specified requirements: achieving client's objectives requires us as developers to understand and implement the correct requirements throughout, not just those initially defined for the project.
- Creating the application that has few defects: among these are bugs that reduce the software’s reliability, compromise its security, or limit its functionality. Achieving zero defects is too much to ask for most projects, but clients are rarely happy with software they perceive as buggy.
- Good enough performance: from a client’s point of view, there’s no such thing as a good, slow application.
- Ease of learning and ease of use: from client's perspective, the software’s user interface is the application, and so these attributes of functional quality are most commonly provided by an effective interface and a well-thought-out user workflow. The aesthetics of the interface—how beautiful it is—can also be important, especially in
  consumer applications.
- Software testing commonly focuses on functional quality: all of the characteristics just listed can be tested, at least to some degree, and so a large part of ensuring functional quality boils down to testing.

(ii) Structural quality means that the code itself is well structured.

- Code testability: Is the code organized in a way that makes testing easy?
- Code maintainability: How easy is it to add new code or change existing code without introducing bugs?
- Code understandability: Is the code readable? Is it more complex than it needs to be?
- Code efficiency: Especially in resource-constrained situations, writing efficient code can be critically important.
- Code security: Does the software allow common attacks such as buffer overruns and SQL injection? Is it insecure in other ways?

(iii) Process quality:

- Meeting delivery dates: Was the software delivered on time?

##### 2. What libraries are being used in the app and why?

##### EXPRESS

FOREVER: CLI tool for ensuring that a given script runs continuously.

NODEMON: a tool that helps develop node.js based applications by automatically restarting the node application when file changes in the directory are detected.

BCRYPTJS: hash passwords

CELEBRATE: celebrate is an express middleware function that wraps the joi validation library. This allows you to use this middleware in any single route, or globally, and ensure that all of your inputs are correct before any handler function.

CORS: a node.js package for providing a Connect/Express middleware that can be used to enable CORS with various options.

DOTENV: Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env

JSONWEBTOKEN: way for securely transmitting information between parties as a JSON object. ... Signed tokens can verify the integrity of the claims contained within it, while encrypted tokens hide those claims from other parties.

MAILGEN: A Node.js package that generates clean, responsive HTML e-mails for sending transactional mail.

MONGOOSE: Mongoose is a MongoDB object modeling tool designed to work in an asynchronous environment.

MORGAN: HTTP request logger middleware for node.js

PASSPORT: Passport is Express-compatible authentication middleware for Node.js. Passport's sole purpose is to authenticate requests, which it does through an extensible set of plugins known as strategies. Passport does not mount routes or assume any particular database schema, which maximizes flexibility and allows application-level decisions to be made by the developer. The API is simple: you provide Passport a request to authenticate, and Passport provides hooks for controlling what occurs when authentication succeeds or fails.

PASSPORT-JWT: A Passport strategy for authenticating with a JSON Web Token. This module lets you authenticate endpoints using a JSON web token. It is intended to be used to secure RESTful endpoints without sessions.

PASSPORT-LOCAL: Passport strategy for authenticating with a username and password. This module lets you authenticate using a username and password in your Node.js applications. By plugging into Passport, local authentication can be easily and unobtrusively integrated into any application or framework that supports Connect-style middleware, including Express.

PASSPORT-LOCAL-MONGOOSE: Passport-Local Mongoose is a Mongoose plugin that simplifies building username and password login with Passport.

VALIDATOR: A library of string validators and sanitizers.

##### REACT

REACT-REDUX : binding React with Redux

REDUX : Tool for State Management. Reasons: a single store is used to keep the state of the app
REDUX-FORM: way to manage your form state in Redux.

REDUX-THUNK: Redux Thunk middleware allows you to write action creators that return a function instead of an action. The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met.

ANT-DESIGN: design creation. Reasons: it provides components, resources and tools for process optimization.

JEST: Javascript Testing solution. Reasons: Tests are created by developers with snapshot is created automatically. If there are differences between tests (ie. snapshots), developers get notified the changes.

##### 3.A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?

###### Technical Skills and Knowledge

(i) A full-stack web developer is a technology expert who can work on both in the front end & back-end of any application.
(ii) Full stack developer helps you to keep every part of the system running smoothly
(iii) Skill sets required to become a Full Stack Developer are Front-end technology, Development Languages, Database, Basic design ability, Server, Working with API and version control systems.

###### Soft skills

(i) Ability to multitask with time constraints
(ii) Good communication skills in order to liaise with client and meet client's expectations
(iii) Ability to work in a team

##### 4. Within your own project what knowledge or skills were required to complete your project, and overcome challenges?

An understanding of how to structure, build and interact with a REST API allowed us to build the foundation of the application. Within both the React frontend and the express backend knowledge of how HTTP requests are made, how to handle and make responses was required to link these two applications effectively. Behind the API is the document based database MongoDB, building this in the right way is very important. Understanding how this style of database differs from a relational database is essential to designing and building an efficient data storage and query system.
The ability to use Debugging tools and processes is essential to increase the quality and speed of development, dealing with errors or bugs early and quickly not allowing them to hinder progress. Aside from technical skills, frequent communication sessions and feedback was one of the most key elements to overcoming any challenges that were encountered throughout the development process.

##### 5. Evaluate how effective your knowledge and skills were this project, using examples, and suggest changes or improvements for future projects of a similar nature?

As a team, we believe we have sufficient knowledge and tools we could use to complete the core goals set out by the client. The key lessons which we learnt from this project are

- Doing it right first means we don’t have to spend time doing it over.
- Placing as much importance on architecture and design as coding ensures the veracity of our project.
- Creating coding standards in order to eliminates unnecessary mistakes.
- Effective peer review ensures errors are minimised before we merge to our development branch
- Testing often allows us to plan further ahead with certainty that errors and bugs have been fixed.
