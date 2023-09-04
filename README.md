# Simple Banking System in C++

This is a simple console-based banking system implemented in C++. It allows users to perform basic banking operations such as opening an account, checking the balance, depositing, and withdrawing money, closing an account, and viewing all accounts. The system uses a class-based approach and stores account data in a file for persistence.

## Features
Create a new account with a unique account number.
Check the balance of an existing account.
Deposit money into an account.
Withdraw money from an account, with a minimum balance requirement.
Close an account and remove it from the system.
View details of all accounts.

## Prerequisites
Before running the program, make sure you have a C++ compiler installed on your system.



## How to Use
1.Compile the program using your C++ compiler. You can use the following command:
```bash
g++ -o banking_system main.cpp
```
2.Run the program:

```bash
./banking_system
```

## File Handling
The program stores account data in a file named "Bank.data" to maintain account information across program executions. The file is created or overwritten when the program starts and is updated each time an account is added, modified, or removed.

## Note
This is a simplified banking system for educational purposes and does not include advanced features like security, user authentication, or transaction history tracking. Additionally, it assumes that account numbers are unique, which may not be the case in a real-world banking system.

Feel free to enhance this system or use it as a starting point for more complex banking applications.
