# employee-management-system
A sample project developed while learning the basics of Spring Framework &amp; Thymeleaf Template Engine.

## Introduction
- This project was developed in the course of learning how to implement Spring Framework in Java.
- I used IntelliJ Idea from JetBrains as the Integrated Development Environment for this project.
- It is built upon Java Development Kit version 22.0.2 using MySQL as Database Management System.
- It utilizes Spring Framework for the backend along with Thymeleaf Template Engine for the frontend.

## Project Details
Without getting into any unnecessary details, here I'll be documenting my thoughts & issues with this project.

### Views
Firstly, I'd like to have it noted that this is a rather simplistic web applications that only has a total of 3 views.
They all have a Navigation Bar that directs you to the 2 primary pages i.e. Employee List page & Add Employee page.

#### Employee List
- There is an Employee List view that serves as an index of all the employees recorded in the database.
- It has 7 columns along with the options to Edit & Delete Employees from the database in the last one.
![Employee List Page](https://github.com/user-attachments/assets/fe6b7af5-0e7d-4d26-8c4d-31d069ea3348)

#### Add Employee & Edit Employee
- This page allows you to Add Employees to the database one at a time. It redirects to the Employee List.
- Along with being used for adding Employees to database, the same layout is also used to Edit Employees.
![Add Employee Page](https://github.com/user-attachments/assets/4488c5e7-5811-45cb-b53c-6e238594835a)

### Issues
Secondly, here I'll be documenting the issues I encountered while developing this web application.
These issues are related to the backend as well as the frontend. I'll discribe them here in brief.
- After describing the entity, repository & service classes, I began creating the 3 main views for the project.
- I had trouble implementing Bootstrap into the web pages as I was trying to run older code with a newer version of Bootstrap.
- I corrected my mistake after figuring out what I was doing wrong following some trial and error and promptly finished working on the views.
- Since, I hadn't connected the templates to the database or defined a contrroller class, I still had more work left as I couldn't test some features/actions.
- So, I started working on the controller class after defining the application properties while simultaneously aiming to finish the templates.
- The controller class was rather easy to define as there weren't many pages or actions to consider, instead the main problem was with the templates.
- I couldn't figure out a way to implement the Serial Number column by myself without using ID which obviously didn't work as intended.
- I had to refer to the Thymeleaf Tutorial to understand how to call Iterator Status variable and use the Count property to properly display the Serial Number.

## Conclusion
- After creating the views, defining the classes and resolving the above issues along with some minor insignificant issues, I was able to finally run the project.
- From this project, I was able to better understand the working of Spring Framwork with Thymeleaf Template Engine along with other suporting tools like Bootstrap.
- Though I also think that just understanding the working of Spring Framework, Thymeleaf Template Engine or Bootstrap is inadequate for developing web applications. 
