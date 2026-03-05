# Employee Payroll App

A Java-based console application for enterprise payroll management, designed using clean, strictly modular Object-Oriented Programming principles.

## Features Implemented

### UC1: Employee Registration
* **Secure Registration:** Implemented employee creation with strict encapsulation, Regex-based input validation (email, phone, ID), and object composition for user credentials.
* **Robust Architecture:** Centralized data persistence via file I/O and utilized a custom `ValidationException` to clearly communicate and handle invalid input errors.

### UC2: User Authentication
* **Secure Login:** Encrypted credential verification using SHA-256 hashing and polymorphic authentication logic for distinct user roles.
* **Session Management:** Implemented secure session handling with timeout validation, login attempt limits, and role-based dashboard redirection.

### UC3: Payslip Generation
* **Payroll Logic:** Designed a comprehensive payroll calculator applying composition and aggregation to link employee profiles with salary components.
* **Automated Processing:** Automated the processing of gross earnings and statutory deductions to generate formatted monthly payslips.

## Tech Stack
* Java

## How to Run
1. Open the project in your IDE.
2. Run the `EmployeePayrollApp.java` main class.