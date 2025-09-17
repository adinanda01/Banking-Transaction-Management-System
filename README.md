🏦 Banking Transaction Management System
A Banking Transaction Management System built with MySQL, demonstrating database design, stored procedures, transactions, access control, and auditing in a banking use-case.

✨ Features

📂 Account Management – Store account balances  
💸 Fund Transfers – Secure transfers with balance validation  
📝 Transaction Logs – Deposits & withdrawals recorded with timestamps  
🔄 Batch Processing – Multiple transfers executed via cursors  
👤 Access Control – Multiple users with specific privileges  
📊 Reports – Withdrawals, deposits, and recalculated balances


📂 Project Files

account.csv – Sample accounts dataset  
trnx.csv – Transfer instructions  
week14.sql – Schema, procedures, reports  
week14.pdf – Reference documentation


🚀 How to Run

Create database
CREATE DATABASE Bank;
USE Bank;


Run the script
SOURCE week14.sql;


Load CSV data into tables

Import account.csv into the account table.
Import trnx.csv into the move_funds table.


Use stored procedures

transfer_funds_1 → Perform single transfer
transfer_funds_2 → Perform transfer with enhanced rules
main_transfer_2 → Process multiple transfers in batch


Generate reports

Deposits per account
Withdrawals per account
Final recalculated balances




🔑 Skills Demonstrated

Database Design (MySQL)
Stored Procedures & Transactions
ACID Properties (Commit/Rollback)
User Privileges & Access Control
Cursors for Batch Processing
Data Integrity & Auditing


🚀 Future Enhancements

Interest calculation & monthly statements
Role-based access (Admin vs Cashier)
Fraud detection triggers
Dashboard for visualization
