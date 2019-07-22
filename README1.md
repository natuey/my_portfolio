[![N|Solid](https://foodladder.org/wp-content/uploads/2018/08/bannerlogo.png)](http://food-ladder-bucket.s3-website-ap-southeast-2.amazonaws.com/)

# CONTENTS

- [Description](#Description)
- [Purpose](#Purpose-of-Food-Ladder-Web-application)
- [Food Ladder Application](#Food-Ladder-application)
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

## Description

Food Ladder is committed to leading the implementation of innovative and sustainable technologies to in-need communities and works exclusively with a host of world-class, tailored and proven products. As Food Ladder expands to other communities around the world, it would like to develop a web application to enhance its communications. So rather than having human resources in each country (which comes at an immense cost), Food Ladder can support communities virtually.

How it would work is communities implement basic greenhouses structures using our blueprint and recommended supplier. We will then provide the know-how and support via manuals (operating guides, education, curriculums etc) and an online platform (website and app) so the system can thrive. This online platform will not only be a tool for communities to speak to our horticulture experts it will also be a self-moderating virtual community, where communities around the world can assist one another, providing growing tips, class ideas etc.

View Food Ladder web application, [please click here](http://food-ladder-bucket.s3-website-ap-southeast-2.amazonaws.com/).
View our Github repos here for [BACK-END](https://github.com/bHarlum/food-ladder-express) and for [FRONT-END](https://github.com/bHarlum/food-ladder-react)

## Purpose of Food Ladder Web Application

To extend Food Ladder's reach by focusing on what they do best, creating social enterprises. Communities or schools will implement basic greenhouse structures, which they pay for, build and maintain. Food Ladder then provide the know-how and support via manuals and an online platform, so the system can thrive.

This online platform will not only be a tool for communities to speak to Food Ladder's horticulture experts it will also be a self-moderating virtual community, where communities around the world can assist one another, providing growing tips, class ideas etc. Food Ladder believe this online solution will thrive in developing countries, with the World Bank finding the poorest households are more likely to have access to mobile phones than to toilets or clean water.

## FOOD LADDER APPLICATION

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

![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/landing.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/login.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/projects_page.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/resources_page.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/forum_page.png?raw=true)

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

![N|Solid](USER WORKFLOW DIAGRAM)

#### Wireframes

View our entire wireframe documents [here](https://drive.google.com/file/d/1Hi-p0L60FumElySOaPAIwwcj_y67mols/view?usp=sharing)

![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/landing_page.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/user_dash.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/project_rego.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/project_dashboard.png?raw=true)

#### Database Diagram

![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/Food%20Ladder%20-%20Database%20Diagram%20v1.png?raw=true)

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

![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/tasks.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/client_meeting.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/stacks.png?raw=true)
![N|Solid](https://github.com/natuey/natuey.github.io/blob/master/users_stories.png?raw=true)

## Short Answer Questions

##### 1. What are the most important aspects of quality software?

###### Reliability

An attribute of resiliency and structural solidity. Reliability measures the level of risk and the likelihood of potential application failures. It also measures the defects injected due to modifications made to the software (its "stability" as termed by ISO). The goal for checking and monitoring Reliability is to reduce and prevent application downtime, application outages and errors that directly affect users, and enhance the image of IT and its impact on a company's business performance.

###### Efficiency

The source code and software architecture attributes are the elements that ensure high performance once the application is in run-time mode. Efficiency is especially important for applications in high execution speed environments such as algorithmic or transactional processing where performance and scalability are paramount. An analysis of source code efficiency and scalability provides a clear picture of the latent business risks and the harm they can cause to customer satisfaction due to response-time degradation.

###### Security

A measure of the likelihood of potential security breaches due to poor coding practices and architecture. This quantifies the risk of encountering critical vulnerabilities that damage the business.[20]

###### Maintainability

Maintainability includes the notion of adaptability, portability and transferability (from one development team to another). Measuring and monitoring maintainability is a must for mission-critical applications where change is driven by tight time-to-market schedules and where it is important for IT to remain responsive to business-driven changes. It is also essential to keep maintenance costs under control.

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

(i) A full-stack web developer is a technology expert who can work on both in the front end & back-end of any application.
(ii) Full stack developer helps you to keep every part of the system running smoothly
(iii) Skill sets required to become a Full Stack Developer are Front-end technology, Development Languages, Database, Basic design ability, Server, Working with API and version control systems.

##### 4. Within your own project what knowledge or skills were required to complete your project, and overcome challenges?

MERN

##### 5. Evaluate how effective your knowledge and skills were this project, using examples, and suggest changes or improvements for future projects of a similar nature?
