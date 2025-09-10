# Bank Account Manager

A small object-oriented **Bank Account Manager** built in Python (Jupyter Notebook).  
This project is part of my journey to revisit OOP concepts and design patterns.  
Future versions will expand into a **Personal Finance Manager** with budgeting, expense tracking, and reports.

## Features
- **Account Creation** – name, account number, initial balance  
- **Basic Operations** – deposit, withdraw, check balance  
- **Account Details** – view account information  
- **Bank Info** – set bank name and track total number of accounts  
- **Transfers** – transfer funds between accounts  
- **Transaction History** – record of deposits, withdrawals, and transfers  
- **Authentication** – PIN system for withdrawals  
- **Account Types** – Savings, Checking, and Joint Accounts

## Getting Started
### Prerequisites
- Python 3.10+
- Jupyter Lab or Notebook

### How to Run
```bash
# clone the repository
git clone https://github.com/Mihret-T/finance-manager.git
cd finance-manager

# launch notebook
jupyter notebook notebooks/bank_account_manager.ipynb
```

## Project Structure
finance-manager/
├─ notebooks/
│  └─ bank_account_manager.ipynb   # project notebook
├─ README.md
├─ requirements.txt
└─ .gitignore

## Design Notes
- Demonstrates OOP principles: encapsulation, inheritance, and polymorphism.
- Uses multiple account types (SavingsAccount, CheckingAccount, JointAccount).
- Includes simple authentication with PIN for secure withdrawals.
- Transaction history shows how state changes can be tracked per account.

## Next Steps
- Refactor into standalone Python modules (src/bank/).
- Add new classes: User, Transaction, Budget.
- Explore design patterns (Factory for account creation, Strategy for interest/fees).
- Add persistence (JSON or SQLite storage).
- Expand into Personal Finance Manager: budgeting, expense tracking, and simple reports.
- 
## Testing (Planned)
- Unit tests will be added using pytest and automated via GitHub Actions.
