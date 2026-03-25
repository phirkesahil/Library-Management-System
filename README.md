# Library Management System

A desktop application built in Java to manage library operations
including book records, member registrations, and issue/return tracking.

## About This Project
Built using Java Swing for the UI and MySQL as the backend database,
this application handles all core library management workflows with
proper validations and data integrity checks.

## Features
- Add, update, search, and delete book records
- Member registration with duplicate member check
- Book issue and return with availability validation
- Automatic overdue fine calculation based on return date
- Search books by title, author, and category

## What I Tested
- All modules manually tested — book issue, return, member registration, and search
- Verified correct behaviour and data integrity across all workflows
- Tested edge cases including duplicate entries and invalid inputs

## Tools & Technologies
- Java
- Java Swing (UI)
- MySQL (Database)
- JDBC (Database Connectivity)

## How to Run
1. Clone the repository
2. Import the SQL file into MySQL to set up the database
3. Update database credentials in the config file
4. Open in IntelliJ IDEA or Eclipse
5. Run `Main.java` to launch the application

## Author
Sahil Avinash Phirke
