# ATM Project

This is a simple ATM simulation project built in Java to help refresh and strengthen my Java programming skills. The application allows users to log in with a customer number and PIN, then access functionalities like viewing balances, withdrawing, and depositing funds in both checking and savings accounts.

## Project Overview

The project consists of three main classes:

- **ATM**: The entry point of the application, which initiates the login process.
- **OptionMenu**: Contains the main menu options, allowing users to select and interact with different account types.
- **Account**: Manages the account details and provides methods for handling deposits, withdrawals, and balance calculations.

## Features

- **User Login**: Users can log in with a predefined customer number and PIN.
- **Account Access**: Access checking and savings accounts.
- **View Balance**: Check the current balance of each account.
- **Withdraw Funds**: Withdraw funds from checking or savings accounts with balance validation.
- **Deposit Funds**: Deposit funds into checking or savings accounts.

## Usage

1. **Run the Application**: Start the program, which will prompt for a customer number and PIN.
2. **Access Account Options**: After login, select an account to view balance, withdraw, or deposit funds.
3. **Exit**: Option to exit the application from the account selection menu.

## Purpose

This project serves as a way to reinforce my foundational Java knowledge by implementing object-oriented programming (OOP) concepts in a practical, hands-on way.

## Requirements

- **Java**: Ensure Java is installed on your machine. This project was developed using Java 17.

## Running the Project

Clone this repository, then compile and run the `ATM` class:
```bash
javac -d bin src/org/example/*.java
java -cp bin org.example.ATM
