# Employee-Management-System

This project is a simple console-based Employee Management System written in C++, designed to manage employees and their assigned projects. It uses doubly linked lists for storing employees and singly linked lists for managing projects assigned to each employee.

# Features

* Add a new employee with a unique ID and name.

* Add a new project to an existing employee.

* Remove an employee and all associated projects.

* Update an employee by adding a new project.

* Display an employee's record including all their projects.

* Display all employees' records in ascending or descending order of IDs.

* Simple and user-friendly menu driven interface.

# How It Works

* Each Employee has:

   * An ID

   * A Name

   * A linked list of projects

* Each Project includes:

   * Project Name

   * Project Code

   * Completion Status (Completed/Not Completed)

* Employees are stored in a doubly linked list, sorted by their ID.

* Projects per employee are stored in a singly linked list.

# Files Included

* Problem1.h — Header file.

* main.cpp — Main source file containing implementation of all functions and program logic.

# How to Run

* Clone or Download the project.

* Open the project folder in any C++ supported IDE (like Visual Studio Code, Code::Blocks, etc.).

# Compile and Run the main.cpp file.

Example compile command:

     g++ main.cpp -o EmployeeManagement
     ./EmployeeManagement

# Sample

![image](https://github.com/user-attachments/assets/65fbbe07-d9ff-496d-b946-638838215058)

![image](https://github.com/user-attachments/assets/4d26b34d-3821-4e22-b9a8-fef2d5a3d04e)


# Notes

* Employees are uniquely identified by their ID.

* Adding a project with an already existing project code is not allowed.

* The system validates user inputs, especially for project completion status (accepts only 0 or 1).

* Order of displaying employees can be ascending or descending based on user preference.
