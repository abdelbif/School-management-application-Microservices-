# School-management-application using Java-SpringBoot-MongDB in a Microservices Architecture

This project involves designing and developing a web-based software system for a school.
The system will allow students to use their scores to receive rewards provided by the school.
The system will have three main types of users: admin staff, teachers, and students.

Admin staff is able to manage schools and teachers on the system, while teachers will be able to manage
their students. Students also will be able to use their scores to purchase avatarelements or other rewards rewards.

## Development
The system is developed using microservices architecture and the following services:
User, School, Teacher, Student, Avatar, Element, and Reward

The system includes standalone client applications for each of the different user types.
The clients will allow users to login, manage schools, manage students, manage avatar
elements, manage rewards, and manage their own avatar.

Additionally, email notifications will be sent to teachers and students when they are added to the system by an
admin or teacher. The system will also have checks in place to ensure that students have enough score to
purchase avatar elements or rewards, and that students cannot purchase more than one reward of the same type.

## Backend Technologies
Programming Language – we used java Microservices Architecture: 
The project is developed as microservices using a technology Spring Boot.
Database: we used NoSQL database MongoDB to store the data.

## Frontend Technologies
I used Postman as a front interact with the back microservices of the project that is for sending HTTP requests to our
microservices and viewing the responses

## Design Patterns
Repository pattern - to implement data access layer and encapsulate the logic that interacts with the database.
Service layer pattern - to implement the business logic of the system and expose the functionalities as APIs to the clients.
