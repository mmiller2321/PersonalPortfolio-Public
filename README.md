# Personal Portfolio
> This project was created using Spring Boot and MongoDB to create a personal portfolio project utilizing Java Spring Boot along with MongoDB. 
> Live demo [_here_](https://micahmiller.herokuapp.com). <!-- If you have the project hosted somewhere, include the link here. -->

## Table of Contents
* [Introduction](https://github.com/mmiller2321/PersonalPortfolio-Public/blob/main/README.md#introduction)
* [Requirements](https://github.com/mmiller2321/PersonalPortfolio-Public/blob/main/README.md#requirements)
    - [Functional Requirements](https://github.com/mmiller2321/PersonalPortfolio-Public/blob/main/README.md#functional-requirements)
    - [Non-Functional Requirements](https://github.com/mmiller2321/PersonalPortfolio-Public/blob/main/README.md#non-functional-requirements)
* [New Technologies](https://github.com/mmiller2321/PersonalPortfolio-Public/blob/main/README.md#new-technologies)
* [Technologies](https://github.com/mmiller2321/PersonalPortfolio-Public/blob/main/README.md#technologies)
* [Tools](https://github.com/mmiller2321/PersonalPortfolio-Public/blob/main/README.md#tools)
* [Technical Approach](https://github.com/mmiller2321/PersonalPortfolio-Public/blob/main/README.md#technical-approach)
* [Risks & Challenges](https://github.com/mmiller2321/PersonalPortfolio-Public/blob/main/README.md#risks--challenges)
* [Issues](https://github.com/mmiller2321/PersonalPortfolio-Public/blob/main/README.md#issues)


## Introduction

What problem were you solving and why were you solving this problem?


# Requirements

## Functional Requirements
- 


## Non Functional Requirements
- 


## New Technologies

- I decided to continue learning about MongoDB by using it within my project for the database to further my knowledge behind how the NoSQL database is used within projects and to figure out why MongoDB is growing in popularity for newer projects. I also, took a datatabase course for SQL and NoSQL and wanted to use my knowledge from that course along with my Java Spring Boot class to integrate it into one project. 

## Technologies

- Java SE - version 15
- Java Spring Boot Framework - version 2.5.5
- HTML5 - Version 5
- CSS3 - Version 3
- Thymeleaf - version 3.0
- MongoDB Compass - version 1.30.1
- Bootstrap - version 5.1
- Jquery - version 3.6.0
<!-- - Three.js - Latest version (MAY REMOVE BEFORE FINAL RELEASE) -->

## Tools

- Jira (Project & Issue Tracking)
- SpringToolSuite4 (Local Development Environment)
- Heroku (Cloud Deployment)
- MongoDB (Cloud Database)
- GitHub (Cloud Project Repository)
- Uptime Robot (Website Monitoring)
- Loggly (Cloud Logging)
- Draw.io (Design diagrams: UML, ER, Wireframes, etc)
- Bootstrap Studio (Created bootstrap pages to be exported into Thymeleaf layout pages)
- Justinmind (Website prototyping)
- MySQL Worbench 8.0 CE (Heroku JawsDB Database local connection)

## Cloud Deployment

- Utilized the Heroku Build Pipeline along with both the Heroku CLI and the built-in Github integration in Heroku for cloud deployment. 
- Used CI/CD with Github and Heroku for automatic build deployments after a git commit was executed. 
- Code was frequently pushed/synced with Github after any changes and after each coding session to keep the cloud repo in Github up to date. 

## Technical Approach

- Began the Java Spring project with implementing login and registration on the website so we can focus on the dynamic pages. Once the project has been successfully connected with the MongoDB database I will setup cloud deployment with the Heroku Cloud to get the project cloud deployed. Once the user is logged in successfully redirect the user to a blog page with the ability to comment on my blog post. Worked with the Java API for the contact and hire me form so once data is submitted successfully send me an email. If I had some more time the next page I'd like to add a technology news page that retrieves articles from a tech news website and pastes it onto a timeline page. May use the Google API for grabbing the news articles or some other third party API. Added a chatbot to the website from a third party to ask the viewer if they want any assistance redirecting to a specific webpage. Created project pages that were finalized to be added as projects to my portfolio project. 

<!-- Project Flowchart -->

<p align="center">
  **Final Flowchart**
  <img src="https://user-images.githubusercontent.com/40038829/167280440-6740a36e-a662-4435-b566-06a4569ba07d.png" width=100% height=100%>
</p>

<p align="center">
  <b>Final Sitemap</b>
  <img src="https://user-images.githubusercontent.com/40038829/167280283-e9f370aa-b557-4506-a5d8-c8259acd62ef.png" width=100% height=100%>
</p>

<p align="center">
  <b>Final UML Class Diagram</b>
  <img src="https://user-images.githubusercontent.com/40038829/167280470-ac0915f7-b3bb-4646-a93a-763781250439.png" width=100% height=100%>
</p>

<p align="center">
  <b>Final Wireframe Diagrams</b>
  <img src="https://user-images.githubusercontent.com/40038829/167280376-f3bd9454-7983-4bbc-8445-51dbe02ba9a3.png" width=100% height=100%>
  <img src="https://user-images.githubusercontent.com/40038829/167280389-abd90d2c-c973-4481-b652-5c2487e9f6a8.png" width=100% height=100%>
</p>

**Bolded text**

__Also bolded text__



## Risks & Challenges

- Had 5 classes this Spring semester and normally has 4 which made it tough to focus on this project along with my other projects in my other classes.
- Time management acrossed all classes and balancing the course work to succeed in each. 
- One Challenge I had was fixing the routing issues throughout the project with the use of a `sitemap.xml` file to add the routes alongside adding them to the appropriate controllers.

## Issues

- Ran into a Registration/Login database connection issue that took awhile to solve tell I decided to switch from a MySQL database to a MondoDB database. 
- Had some problems with integrating the Bootstrap studio design (HTML, CSS, JS) into the Java project through the use of Thymeleaf layouts and modifying them to support the bootstrap design. 

