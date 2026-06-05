# SecureATM

A console-based ATM Management System built in C++ that simulates core banking operations such as account creation, user authentication, deposits, withdrawals, PIN management, balance inquiry, and transaction history tracking.

The project focuses on secure account handling, modular software design, file-based data persistence, and transaction auditing.

## Features

* Secure account creation and login system
* PIN encryption and authentication
* Masked PIN input for enhanced security
* Deposit and withdrawal operations
* Balance inquiry functionality
* PIN change with verification
* Account name update support
* Transaction history tracking with timestamps
* Persistent storage using text files
* Input validation and error handling
* Modular function-based architecture

## Technologies Used

* C++
* Object-Oriented Programming (OOP) Concepts
* File Handling
* Data Structures (Vectors)
* Modular Programming

## Project Structure

```
SecureATM/
│
├── main.cpp
├── accounts.txt
├── transactiondetails.txt
└── README.md
```

### Files

#### main.cpp

Contains the complete implementation of the ATM Management System, including:

* User authentication
* Account management
* Transaction processing
* File operations
* Security features
* Transaction logging

#### accounts.txt

Stores account information:

```
AccountNumber EncryptedPIN Name Balance
```

#### transactiondetails.txt

Stores transaction records:

```
AccountNumber TransactionType Amount RemainingBalance Date Time
```

## Security Features

* Encrypted PIN storage
* PIN verification before sensitive operations
* Hidden PIN entry using masked input
* Input validation to prevent invalid transactions
* Transaction logging for auditing and traceability

## Key Functionalities

### Account Management

* Create new account
* Login authentication
* Change account holder name
* Change PIN securely

### Banking Operations

* Deposit money
* Withdraw money
* Check account balance

### Transaction Tracking

* Automatic transaction logging
* Date and time stamping
* View recent transaction history
* Track remaining account balance after each transaction

## Design Highlights

* Organized into 20+ modular functions for better maintainability
* Separation of concerns between authentication, transaction processing, and file management
* In-memory account processing with controlled file synchronization
* Clean and readable code structure for easier debugging and future enhancements

## Future Improvements

* Convert structures into fully encapsulated classes
* Implement account-to-account money transfer
* Add admin dashboard
* Replace text-file storage with SQLite database
* Improve PIN encryption using cryptographic hashing
* Introduce role-based access control
* Develop a graphical user interface (GUI)

## How to Run

### Compile

```bash
g++ main.cpp -o ATM
```

### Execute

```bash
./ATM
```

## Learning Outcomes

This project helped strengthen understanding of:

* C++ programming
* Object-Oriented Design
* File Handling
* Data Persistence
* User Authentication
* Modular Software Development
* Input Validation and Error Handling

## Author
Vikash Patel
