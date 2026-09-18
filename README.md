🧑‍💼 Employee Management System (Java Console Application)
📌 Project Description

The Employee Management System is a Java-based console application developed using Object-Oriented Programming (OOP) principles and the DAO (Data Access Object) design pattern.
This project allows an organization to manage employee records efficiently by performing CRUD operations, calculating salary-based bonuses, and handling different employee roles such as Employees and Managers.

The application is designed with a clean package structure, proper exception handling, and a menu-driven console interface for better usability and maintainability.

🎯 Features Implemented

Auto-generated Employee ID

Add Employee and Manager

Display all Employees

Search Employee by ID (Name & Salary)

Update Employee Salary

Delete Employee by ID

Bonus calculation based on role:

Employee → 10% of salary

Manager → 20% of salary

Custom Exception handling (EmployeeNotFoundException)

Clean and user-friendly console menu

DAO pattern for separation of concerns

🧠 Core Concepts & Logic Used
🔹 Object-Oriented Programming (OOP)

Inheritance: Manager class extends Employee

Polymorphism: Bonus calculation overridden for Manager

Encapsulation: Private/protected fields with getters and setters

Abstraction: DAO interface hides implementation details

🔹 DAO Design Pattern

EmployeeDao interface defines operations

EmployeeDaoImpl handles all data logic

Helps in loose coupling and easy scalability

🔹 Auto-Generated Employee ID

Employee ID is generated automatically inside DAO using a static counter

Ensures uniqueness and avoids manual ID entry

Keeps ID management away from UI layer

🔹 Exception Handling

Custom runtime exception EmployeeNotFoundException

Thrown when an employee ID is not found

Improves reliability and error clarity

📂 Project Structure
src
 └── org.ycpait.employeemanagement
      ├── MainApp.java
      ├── dao
      │     ├── EmployeeDao.java
      │     └── EmployeeDaoImpl.java
      ├── entity
      │     ├── Employee.java
      │     └── Manager.java
      └── exception
            └── EmployeeNotFoundException.java

🖥️ How to Run the Project

Clone the repository

git clone <repository-url>


Open the project in Eclipse / IntelliJ

Run MainApp.java

Use the console menu to perform operations

🚀 Future Enhancements

File handling (store employee data in .txt file)

JDBC + Database integration

Spring Boot REST API version

Sorting & filtering employees

JUnit test cases

GUI or Web-based UI

🛠️ Technologies Used

Java (JDK 21)

Core Java

OOP Concepts

DAO Pattern

Exception Handling

Console-based UI

👨‍💻 Author


Java Developer | Backend Enthusiast

⭐ If you like this project, don’t forget to star the repository!
