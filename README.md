# Expense Tracker

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Description

Expense Tracker is a simple React application that allows you to keep track of your income and expenses. The app provides an overview of your balance, income, and expenses, and allows you to add and delete transactions.

## Features

- Track income and expenses
- View current balance
- Add new transactions (income/expense)
- Delete transactions
- Responsive design

## Installation

### Prerequisites

Make sure you have the following software installed:

- [Node.js](https://nodejs.org/en/download/)


### Project Structure

expense_tracker/
├── node_modules/
├── public/
│   ├── index.html
│   ├── ...
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── Balance.js
│   │   ├── IncomeExpenses.js
│   │   ├── TransactionList.js
│   │   ├── Transaction.js
│   │   ├── AddTransaction.js
│   ├── context/
│   │   ├── AppReducer.js
│   │   ├── GlobalState.js
│   ├── App.css
│   ├── App.js
│   ├── index.css
│   ├── index.js
├── package.json
└── README.md

### Components
- Header.js: Displays the title of the application.
- Balance.js: Displays the current balance.
- IncomeExpenses.js: Displays the total income and expenses.
- TransactionList.js: Displays the list of transactions.
- Transaction.js: Displays a single transaction.
- AddTransaction.js: Form to add a new transaction.


### Clone the Repository

```bash
git clone https://github.com/your-username/expense_tracker.git
cd expense_tracker
npm install
npm start