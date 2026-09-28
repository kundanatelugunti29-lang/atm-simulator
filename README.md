# ATM Simulator

A simple console-based ATM Simulator developed using Python. This project allows users to perform basic ATM operations such as checking balance, depositing money, and withdrawing money through a simple menu-driven interface.

## 📌 Project Description

The ATM Simulator is a Python-based application designed to demonstrate basic ATM operations using Object-Oriented Programming (OOP).

The project is useful for beginners to understand how classes, objects, methods, loops, conditional statements, input validation, and exception handling can be used together to create a simple real-world application.

## 🚀 Features

- Check account balance
- Deposit money
- Withdraw money
- Prevent withdrawals with insufficient funds
- Prevent zero or negative transactions
- Menu-driven interface
- Handle invalid user input
- Exit the application safely

## 🛠️ Technologies Used

- Python 3
- Object-Oriented Programming (OOP)
- Console / Command-Line Interface

## 🧠 Python Concepts Used

- Classes and Objects
- Constructor (`__init__`)
- Methods
- Variables
- Conditional Statements
- `while Loop'
- `if-elif-else'
- `try-except'
- User Input
- Exception Handling
- Input Validation

## 📁 Project Structure

ATM-Simulator/
│
├── atm.py
└── README.md

## ▶️ How to Run

### 1. Install Python

Make sure Python 3 is installed on your computer.

### 2. Clone the Repository

``bash
git clone https://github.com/your-username/ATM-Simulator.git

3. Open the Project Folder
cd ATM-Simulator

4. Run the Program
python atm.py

⚙️ How It Works
- The application starts with a balance of $0.

- The ATM menu is displayed.

- The user selects an option.

- The selected operation is performed.

- The application validates the entered amount.

- The balance is updated after a successful transaction.

- The menu is displayed again.

- The program continues until the user selects Exit.

💳 ATM Operations
1. Check Balance
Displays the user's current account balance.

2. Deposit
Allows the user to enter an amount and add it to the account balance.

The program does not accept zero or negative deposit amounts.

3. Withdraw
Allows the user to withdraw money from the account.

The withdrawal is rejected if:

The amount is zero or negative.

The withdrawal amount is greater than the available balance.

4. Exit
Closes the ATM application and displays a thank-you message.

⚠️ Error Handling
The program handles invalid input using Python's try-except mechanism.

For example:

Invalid numbers

Negative amounts

Zero amounts

Insufficient funds

The user receives an appropriate error message and can try again.

🔮 Future Improvements

- Add PIN authentication

- Add multiple user accounts

- Add transaction history

- Store account data permanently

- Add money transfer functionality

- Add account creation

- Connect the application to a database

- Create a graphical user interface (GUI)

ATM Simulator
Integrated Skills: Python Programming and Object-Oriented Programming
🎓 Purpose
This project is created for educational and learning purposes.

It demonstrates how basic Python programming concepts can be combined to develop a simple ATM simulation.

The project focuses on understanding:

Object-Oriented Programming

Classes and Objects

Methods

Loops and Conditions

Input Validation

Exception Handling

Basic Application Structure

📚 Learning Outcomes
After completing this project, beginners can understand how to:

- Create and use Python classes
Define methods for different operations

- Manage data using object attributes

- Validate user input

- Handle errors using exceptions

- Build a menu-driven console application

- Separate application logic from user interaction

🏗️ Project Architecture
The project contains two main classes.

ATM
The ATM class is responsible for managing the account balance and performing basic ATM operations.

It includes:

- Checking balance

- Depositing money

- Withdrawing money

- Validating transactions

- Managing the current balance

ATMController
The ATMController class is responsible for handling user interaction and controlling the application.

It includes:

- Displaying the ATM menu

- Taking user input

- Calling ATM operations

- Handling errors

- Controlling the program flow

🔄 Basic Flow
Start
↓
Display ATM Menu
↓
User Selects Option
↓

Check Balance

Deposit

Withdraw

Exit
↓
Perform Selected Operation
↓
Display Result
↓
Return to Menu
↓
Exit

💡 Example Menu

Welcome to the ATM!

Check Balance

Deposit

Withdraw

Exit

Please choose an option:

📖 Project Highlights
This project provides practical experience with Python programming and demonstrates how Object-Oriented Programming can be used to organize a small application.

The program keeps the ATM operations inside the ATM class while the ATMController class manages user interaction. This separation makes the code easier to understand and maintain.

👨‍💻 Author
TELUGUNTI KUNDANA
INTEGRATED MTECH ARTIFICIAL INTELLIGENCE
VIT BHOPAL UNIVERSITY

📄 License
This project is created for educational and learning purposes.
