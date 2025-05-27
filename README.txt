Basic Banking System

Project Description

This is a GUI-based banking system developed in Java using KL4-style object-oriented classes. It supports two types of accounts: Savings and Current, and allows the user to perform basic banking operations such as deposit, withdrawal, and balance inquiry. Proper access control and encapsulation are implemented through private data members and public methods.

Features

Savings & Current Account Management

Deposit Functionality

Withdrawal with Balance Check

Balance Inquiry

Database Connectivity using JDBC

GUI Interface using Java Swing


Tech Stack

Java (JDK 11+)

MySQL (for persistent storage)

JDBC (for database interaction)

Swing (for GUI)

MVC Architecture (Model-View-Controller)

Project Structure

BasicBankingSystem/
│
├── src/
│   ├── dao/              # Data Access Object for DB operations
│   ├── model/            # KL4-based Account class
│   ├── ui/               # GUI layout using Swing
│   ├── utils/            # DB connection class
│   └── Main.java         # Entry point


---

Database Design

Database Name: banking_system

Table: accounts

acc_number (Primary Key)

name (Account holder name)

acc_type (Savings or Current)

balance (Current balance)


How It Works

1. Deposit: Adds amount to the current balance.


2. Withdraw: Deducts amount if sufficient balance exists.


3. Balance Inquiry: Retrieves current balance from the database.


4. All operations use JDBC to interact with MySQL securely.


5. GUI allows user-friendly access to the system.

GUI Details

Built using Swing for desktop interfaces.

Includes text fields for account input and amount.

Buttons for each operation with live status display.

Simple layout, clean aesthetics, and basic responsiveness.


Setup Instructions

1. Clone the repo.


2. Set up MySQL and create the accounts table.


3. Replace the database credentials in the DBConnection class.


4. Compile and run Main.java.


JDK & IDE Setup ✅

Project Structure ✅

Database Schema & MySQL Table ✅

JDBC Integration ✅

Model & DAO Classes ✅

UI Design (Swing) ✅

Component Alignment ✅

Responsiveness & Accessibility ✅

