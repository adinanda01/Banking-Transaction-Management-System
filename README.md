# Banking-Transaction-Management-System

A Banking Transaction Management System built with MySQL, demonstrating database design, stored procedures, transactions, access control, and auditing in a banking use-case.

✨ Features

📂 Account Management – store account balances.

💸 Fund Transfers – secure transfers with balance validation.

📝 Transaction Logs – deposits & withdrawals recorded with timestamps.

🔄 Batch Processing – multiple transfers executed via cursors.

👤 Access Control – multiple users with specific privileges.

📊 Reports – withdrawals, deposits, and recalculated balances.

📂 Project Files

account.csv – sample accounts dataset

trnx.csv – transfer instructions

week14.sql – schema, procedures, reports

week14.pdf – reference documentation

🚀 How to Run

Create database:

CREATE DATABASE Bank;
USE Bank;


Run the script:

source week14.sql;


Load CSV data into tables (account, move_funds).

Use stored procedures (transfer_funds_1, transfer_funds_2, main_transfer_2) to perform transactions.

Generate reports for deposits, withdrawals, and final balances.

🔑 Skills Demonstrated

Database Design (MySQL)

Stored Procedures & Transactions

ACID Properties (Commit/Rollback)

User Privileges & Access Control

Cursors for Batch Processing

Data Integrity & Auditing

🚀 Future Enhancements

Interest calculation & monthly statements

Role-based access (admin vs cashier)

Fraud detection triggers

Dashboard for visualization
