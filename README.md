# OSDBMS Project – MySQL Backup & Restore Simulation

## Student Details

Name: Ayesha Vanjre
Class: SYIT
Roll No: 2542050
Subject: OSDBMS
Academic Year: 2025–2026

---

## Project Title

MySQL Backup & Restore Simulation

---

## Project Description

This project demonstrates how database backup and recovery works using MySQL.
A sample database named **AmulDB** is created with multiple related tables such as Brand, Product, Customer, Orders, and OrderDetails.

The project shows:

* Database design using normalization (3NF)
* Table creation using SQL
* Data insertion
* Backup using mysqldump
* Data loss simulation (database deletion)
* Restore using backup file

This simulation proves that even if a database is deleted, it can be recovered safely using proper backup techniques.

---

## Database Name

AmulDB

---

## Tables Used

* Brand
* Product
* Customer
* Orders
* OrderDetails

---

## SQL Concepts Used

* CREATE DATABASE
* CREATE TABLE
* INSERT INTO
* PRIMARY KEY
* FOREIGN KEY
* AUTO_INCREMENT
* Normalization (3NF)

---

## Tools & Software Used

* MySQL Server
* MySQL Workbench
* Windows OS
* SQL

---

## Backup Command Used

mysqldump -u root -p AmulDB > amul_backup.sql

---

## Restore Command Used

mysql -u root -p AmulDB < amul_backup.sql

---

## How to Run This Project

1. Install MySQL Server and MySQL Workbench
2. Open MySQL Workbench
3. Run the SQL script file provided in this repository
4. Database and tables will be created
5. Insert data using given queries
6. Run backup command in command prompt
7. Delete database to simulate data loss
8. Run restore command to recover database

---

## Repository Contents

* SQL Script File
* Backup SQL File
* Project Documentation (PDF)
* Screenshots
* README file

---

## Conclusion

This project successfully demonstrates MySQL backup and restore process. It highlights the importance of data safety, recovery, and database reliability using open source DBMS tools.

---
