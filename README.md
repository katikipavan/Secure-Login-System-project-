# Secure Login System

## Overview

A secure login web application built using Python, Flask, SQLite, and bcrypt. The system allows users to register, log in securely, and manage sessions.

## Features

* User Registration
* User Login
* Password Hashing using bcrypt
* SQLite Database Storage
* SQL Injection Protection using Parameterized Queries
* Session Management
* Logout Functionality

## Technologies Used

* Python
* Flask
* SQLite
* bcrypt
* HTML

## Project Structure

SecureLoginSystem/
│
├── app.py
├── users.db
├── templates/
│   ├── register.html
│   ├── login.html
│   └── dashboard.html
└── README.md

## Installation

1. Install Python
2. Install required packages:

pip install flask bcrypt

3. Run the application:

python app.py

4. Open the browser:

http://127.0.0.1:5000

## Security Features

### Password Hashing

Passwords are hashed using bcrypt before storing them in the database.

### SQL Injection Protection

Parameterized SQL queries are used to prevent SQL injection attacks.

### Session Management

User sessions are maintained securely using Flask sessions.

### Logout Feature

Users can securely log out and terminate active sessions.

## Future Improvements

* Two-Factor Authentication (2FA)
* Password Reset via Email
* Email Verification
* Account Lockout after Multiple Failed Attempts

## Author

Pavan Kumar
 
