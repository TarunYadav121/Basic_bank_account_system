# Basic_bank_account_system
Banking Application
Author

Name: Tarun Yadav
Roll No: 2401350015

📋 Project Overview

This is a simple console-based Banking Application in Java.
It allows users to:

Create new bank accounts

Deposit and withdraw money

View account details

Update contact information

Each account is automatically assigned a unique account number starting from 1001.

🛠 Features

Create Account – Add a new customer account with name, email, phone number, and initial deposit.

Deposit Money – Add money to an existing account.

Withdraw Money – Withdraw money from an account (only if sufficient balance).

View Account Details – Display account number, holder name, balance, email, and phone number.

Update Contact Details – Change the email or phone number of an account holder.

Exit – Close the application safely.

🗂 Project Structure
BankingApplication/
│
├─ Account.java       // Class that defines the Account structure and operations
├─ UserInterface.java // Handles user interaction and menu-driven operations
└─ README.md          // Project documentation


(In the provided code, both classes are in a single file for simplicity.)

💻 How to Run
Prerequisites

Install Java JDK 8+.

A terminal or IDE (e.g., IntelliJ, Eclipse, VS Code) with Java support.

Steps

Save the code in a file named UserInterface.java.

Open terminal in the file’s directory.

Compile the program:

javac UserInterface.java


Run the program:

java UserInterface

🧩 Sample Menu

When the program runs, you will see:

Welcome to the Banking Application!
1. Create a new account
2. Deposit money
3. Withdraw money
4. View account details
5. Update contact details
6. Exit
Enter your choice:


Follow the instructions to perform operations.

⚠️ Notes

Maximum 100 accounts can be created (fixed array size).

Deposits and withdrawals must be positive amounts.

Withdrawal is not allowed if balance is insufficient.

Account numbers are auto-generated sequentially.

🏁 Example Run
Enter your choice: 1
Enter account holder name: Rahul Sharma
Enter initial deposit amount: 5000
Enter email address: rahul@gmail.com
Enter phone number: 9876543210
Account created successfully with Account Number: 1001

📚 Concepts Used

Object-Oriented Programming (OOP) – Classes, Objects, Encapsulation.

Array Data Structure – To store multiple account objects.

Scanner Class – For user input.

Switch-Case – Menu-driven program control.

✍️ Author

Tarun Yadav – B.Tech Student (Roll No: 2401350015)
