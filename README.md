# Banking System with Fraud Detection

## Project Overview

The **Banking System with Fraud Detection** is a relational database project developed using **MySQL**. This project is designed to manage banking operations such as maintaining customer information, bank accounts, debit/credit cards, and financial transactions while identifying suspicious activities through fraud detection techniques.

The database demonstrates the implementation of:

* Database creation
* Table creation
* Primary and Foreign Keys
* Data insertion
* Table relationships
* SQL queries of different difficulty levels
* Fraud detection using SQL

---

## Technologies Used

* MySQL
* SQL

---

## Database Tables

The project contains the following tables:

1. Customers
2. Accounts
3. Cards
4. Transactions

---

## Table Description

### Customers

Stores customer information including personal details, contact information, KYC status, and account creation date.

### Accounts

Maintains bank account details such as account number, account type, balance, status, and opening date. Each account belongs to one customer.

### Cards

Stores debit and credit card details linked to customer accounts, including card number, card type, CVV, and expiry date.

### Transactions

Maintains all banking transactions including deposits, withdrawals, amount, transaction date, merchant details, device information, transaction location, and transaction status.

---

## Relationships

* One customer can own multiple accounts.
* One account can have one or more debit/credit cards.
* One account can perform multiple transactions.
* Transactions are linked to accounts for banking analysis and fraud detection.

---

## SQL Concepts Implemented

### DDL (Data Definition Language)

* CREATE DATABASE
* CREATE TABLE
* PRIMARY KEY
* FOREIGN KEY

### DML (Data Manipulation Language)

* INSERT
* UPDATE
* DELETE

### DQL (Data Query Language)

* SELECT
* WHERE
* ORDER BY
* GROUP BY
* HAVING

### Aggregate Functions

* COUNT()
* SUM()
* AVG()
* MAX()
* MIN()

### Joins

* INNER JOIN
* Multiple Table JOIN

### Advanced SQL

* Subqueries
* Common Table Expressions (CTEs)
* Window Functions
* Running Balance
* Fraud Detection Queries

---

## SQL Queries Included

### Easy Level Queries

Queries using:

* WHERE clause
* Comparison Operators
* ORDER BY
* Basic Filtering
* Aggregate Functions

### Intermediate Level Queries

Queries using:

* INNER JOIN
* GROUP BY
* COUNT()
* SUM()
* AVG()
* MAX()
* MIN()
* Subqueries

### Advanced Level Queries

Queries using:

* Window Functions
* RANK()
* DENSE_RANK()
* ROW_NUMBER()
* LAG()
* LEAD()
* Running Balance
* Fraud Detection Queries
* Common Table Expressions (CTEs)

---

## Fraud Detection Features

The project includes SQL queries to identify suspicious banking activities such as:

* High-value transactions
* Large debit transactions
* Multiple transactions within a short time period
* Transactions from different locations
* Running balance calculation
* Multiple device usage detection
* Failed transaction monitoring
* Unusual customer transaction behavior
* Suspicious account activity

---

## Features

* Real-world Banking Database Design
* Customer Management
* Account Management
* Debit/Credit Card Management
* Transaction Management
* Fraud Detection using SQL
* Proper use of Primary and Foreign Keys
* Sample data inserted for testing
* ER Diagram included
* Easy, Intermediate, and Advanced SQL queries
* Well-structured relational database

---

## Learning Outcomes

Through this project, the following database concepts were practiced:

* Database Design
* Relational Database Management
* Database Normalization
* Primary and Foreign Keys
* SQL Query Writing
* Filtering and Sorting
* Aggregate Functions
* GROUP BY and HAVING
* JOIN Operations
* Subqueries
* Window Functions
* Fraud Detection Logic
* Banking Transaction Analysis
* ER Diagram Design

---

## Future Enhancements

The project can be extended by adding:

* Loan Management Module
* Branch Management
* Employee Management
* ATM Transactions
* Internet Banking
* UPI Payments
* OTP Authentication
* User Login System
* Automatic Fraud Alert Generation
* Stored Procedures
* Triggers
* Transactions (COMMIT & ROLLBACK)

---

## Authors

This project was collaboratively developed by the following team members:

| Team Member | Contribution                                                                                                             |
| ----------- | ------------------------------------------------------------------------------------------------------------------------ |
| **Deepthi** | Designed the database schema, created SQL tables, implemented relationships, and developed core banking queries.         |
| **Reshma**  | Developed transaction management queries, inserted sample data, and performed database testing and validation.           |
| **Sai**     | Implemented fraud detection queries, analyzed suspicious transactions, and optimized SQL queries for better performance. |
| **Bhavana** | Designed the ER diagram, prepared project documentation, verified database integrity, and assisted in query testing.     |

---

## Conclusion

The **Banking System with Fraud Detection** project demonstrates the practical implementation of MySQL concepts through a real-world banking application. It covers database design, relational modeling, transaction management, SQL query development, and fraud detection techniques. This project serves as an excellent academic and portfolio project for understanding modern database management systems and advanced SQL concepts.
