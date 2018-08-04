# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions
Once you have finished your project outline, commit and push your changes to your repository and submit the assignment on Canvas by submitting the URL to your outline. Your mentor will provide feedback after the assignment deadline.

### Overview
My project will be a contractor and volunteer management tool that helps LaunchCode impact team in finding, tracking, and managing the instructors, teaching assistants, and volunteers for our education programs and events. It will allow LaunchCode staff members to create events such as a class or mock interview event, with details including data/time, location and numbers of contractors / volunteers needed. It will also allow the LaunchCode community to view those events and sign up for classes they want to teach or events they can help with. 

This project is motivated by the cumbersome outreach efforts within our team at LaunchCode in recruiting contract course staff and volunteers. Currently, we compile a list of classes and events every once in a while and send those to individuals within our network. We then track the responses in a spreadsheet for each upcoming program. I am hoping that this application could serve as a centralized tool to manage those efforts for both our team and the community who want to engage with us by teaching and volunteering. 

### Features
* View events: All users can see the list of upcoming programs, classes and events without logging in.  
* User login: Users will be able to log in by creating accounts in the system. There are two types of users - admin users (LaunchCode staff) and regular users. Admin users can create, edit and delete events (see below). Regular users can sign up for classes they want to teach or events they want to volunteer at.  
* Create events: Admin users will be able to create new events in the system by entering in a mixture fields, such as title, description, date, time, location, number of staff or volunteer needed, etc. A new event will be in draft mode (invisible on the webpage) at the time of creation because it is subject to change. After all event details have been finalized, admin users can confirm to make the event public on the webpage.  
* Edit and delete events: Admin users can edit or delete events when they are in draft mode. 
* Sign up for events: Users will be able to sign up for events on the website.  
* Manage contractors and volunteers: Admin users can see who signed up for a particular event, and then confirm or delete their shift. 

### Technologies
* Java  
* Spring Boot  
* MySQL  
* Thymeleaf templates  
* Bootstrap

### What I'll Have to Learn
I will need to learn the login approach in Java Spring Boot and how to set up different permission sets for different types of users. I have never worked with Date or Time classes in Java, and anticipate to learn about those as well. 

### Project Tracker 
The progress of my project can be tracked at this [Trello Board](https://trello.com/b/oHpfvhqZ/my-capstone-project).