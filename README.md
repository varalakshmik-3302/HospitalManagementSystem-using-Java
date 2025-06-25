# Hospital Management System

## Overview

The **Hospital Management System** is a Java-based console application designed to manage and maintain information about doctors and patients. The project leverages core Java concepts along with **JDBC (Java Database Connectivity)** to interact with a backend database securely using **Prepared Statements**.

This project aims to demonstrate practical implementation of object-oriented design and database operations in Java.

## Objectives

- To simulate a basic hospital record management system.
- To enable CRUD (Create, Read, Update, Delete) operations on patient and doctor records.
- To implement secure and efficient database communication using JDBC and PreparedStatement.

## Key Modules

- **Doctor.java**: Defines the doctor entity and its attributes.
- **Patient.java**: Defines the patient entity and its attributes.
- **HospitalManagementSystem.java**: Acts as the main controller for menu-driven user interaction and database operations.
- **JDBC Integration**: Handles connection setup, query execution, and data retrieval from the underlying database.

## Features

- Add new doctor and patient records to the database.
- Retrieve and display stored records.
- Uses **PreparedStatement** to prevent SQL injection and enhance query performance.
- Modular, object-oriented design.
- Console-based interface with user-friendly prompts.

## Database Integration

- **Technology**: JDBC (Java Database Connectivity)
- **Driver**: MySQL JDBC Driver (or appropriate for your database)
- **Operations**:
  - Establishing secure connections using `DriverManager`
  - Executing parameterized queries with `PreparedStatement`
  - Handling `ResultSet` for data retrieval

> Ensure the database is configured correctly and the necessary JDBC driver is added to the classpath.

## Technology Stack

- **Programming Language**: Java
- **Database**: MySQL (or any relational database)
- **JDBC Driver**: MySQL Connector/J
- **IDE**: Visual Studio Code, IntelliJ IDEA, or Eclipse

## How to Compile and Run

1. **Configure Database**: Create required tables and schema before running the application.

2. **Compile the project**:
  
   javac HospitalManagementSystem.java 


3. **Run the application**:

   java HospitalManagementSystem
   

4. **Ensure JDBC driver is available** in your classpath if running from command line.




