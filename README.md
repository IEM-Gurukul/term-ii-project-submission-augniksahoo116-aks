[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/pG3gvzt-)
# PCCCS495 – Term II Project

## Project Title

Library Management System

## Problem Statement (max 150 words)

Managing library records manually can be diﬃcult and me-consuming, especially when handling
many books and tracking their issue and return status. A digital system is needed to organize book
informa on eﬃciently and reduce errors. The proposed Library Management System will allow users
to add, view, issue, return, and remove books using a structured Java applica on. The system will
apply Object-Oriented Programming concepts and collec ons to manage library data in a simple and
eﬃcient way.

## Target User
Librarians managing library records
Students accessing library books
Educatonal ins tu ons and small libraries
Library administrators


## Core Features
Add new books to the library
View all available books
Issue books to users, Return issued books
Remove books from the system
Display book details such as ID, tle, author, and issue status



## OOP Concepts Used

- Abstraction: Library operations such as adding, issuing, and returning books are handled
through service classes, hiding internal implementation details from the user.
- Inheritance: Classes can extend base classes (for example, different types of users or library
items) to reuse common properties and behaviors.
- Polymorphism: Method overriding or interface implementation allows different classes to
provide their own implementation of common operations.
- Exception Handling: Try–catch blocks and custom exceptions will handle errors such as
issuing unavailable books or accessing non-existent records.
  



## Proposed Architecture Description
The system will follow a modular architecture where different components of the
program are separated into packages such as model, service, util, and main. The model
layer represents the book data structure, the service layer handles library operations like
adding or issuing books, the utility layer manages custom exceptions, and the main layer
controls the user interface and program execution. This modular design improves readability,
maintainability, and scalability of the application while clearly separating responsibilities
among different components of the system.

## How to Run
Run this project by first installing Java JDK (8 or above) and opening the project in any IDE like IntelliJ, Eclipse, or VS Code. Compile the source files and execute the main class (e.g., Main.java) either using the IDE’s run option or through the terminal using javac and java commands. Once executed, the GUI-based Library Management System will launch, allowing you to perform operations like adding, issuing, and returning books.

## Git Discipline Notes
1. Initial project setup with folder structure and README  
2. Added Book class with basic attributes and methods  
3. Implemented User class for library members  
4. Created Library class to manage books and users  
5. Added functionality to issue and return books  
6. Implemented search feature for books  
7. Designed basic GUI layout using Swing  
8. Integrated backend logic with GUI actions  
9. Fixed bugs and improved input validation  
10. Final code cleanup and project documentation update
