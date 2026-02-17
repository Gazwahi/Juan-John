# CISC 4900 Final Project
Senior project for CISC 4900 – research, code, experiments, and documentation.

# Project Overview
This project is a small fullstack informational webpage that will display the business in a clean, and professionl look, with a online feature for customers to submit submissions for documents, and a admin login portal to review submissions, with status updates and email notifications for submissions. 

This project is for a funeral home business, looking to have a professional webpage. Staff currently has customaers fill out the basic informational forms in-person, which can lead to delays. 

With this project i am aiming to help create a simple system, in which the funeral home can use to neatly display what their business offers, and a way in which the customers can fill out forms online which automatically will be emailed to staff. 

# Problem
Staff Currently: Does not have a website, and has customers fill out forms in person. 
This leads to: 
- Chance of papers getting lost
- No organization
- Delays

The goal is to create something visually pleasing, that customers will find simple and informational, and a system that will ease staffs work processes.

# Solution
How will i approach this?
- Will be using HTML, CSS, and Javascript for the front-end, to create something clean and professional.
- User will fill out informational forms on the website.
- Admins will be able to retrieve this data in an online portal.
- Submission details will be notified to staff via email.
- Cleanly organzied.

# Tech Stack
*Roughly

Frontend: VS code IDE
- HTML, CSS, JavaScript

HTML: Site structure/Skeleton. Content and pages
CSS: Design and Layout. Colors, fonts etc. 
JS: Interaction & Movement: Navigation Bar open/close, animation, form validation, scroll effects, etc (undecided)

Backend:
- Spring framework, Thymeleaf, PostgreSQL, SendGrid

Spring Boot: Java backend framework for checklist/admin portion.
Spring Web: Web requests, (GET,POST)
Spring Data JPA: Connects java app to database
Spring Security: Protects staff portal, admin login, password encryption, protected pages
ThymeLeaf: how Spring Boot generates admin pages
PostgreSQL: database where everything is stored, form submission, admin account, status
Validation: required formatting and validity
SendGrid: automatic email sender

Tools:
- Netlify, Railway, Github

Netlify: Upload site to make live.
Railway: server for Spring Boot and PostgreSQL, backend lives online
Github: Project and Repository

# Current Status 
- Working on HTML Skeleton
- Gathering information for next steps

# Next Steps
- Finish up the front end
- Starting Springboot and database
- Checklist forms & Admin Login
- Set up email notifs
- Final testings and deploy

# Author
Gazwah Ishtiaq
CISC 4900 – Spring 2026
Brooklyn College
