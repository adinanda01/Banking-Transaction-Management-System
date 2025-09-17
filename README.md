# 🏦 Banking-Transaction-Management-System

A **Banking Transaction Management System** built with **MySQL**, demonstrating **database design, stored procedures, transactions, access control, and auditing** in a banking use-case.

---

## ✨ Features
- 📂 **Account Management** – store account balances  
- 💸 **Fund Transfers** – secure transfers with balance validation  
- 📝 **Transaction Logs** – deposits & withdrawals recorded with timestamps  
- 🔄 **Batch Processing** – multiple transfers executed via cursors  
- 👤 **Access Control** – multiple users with specific privileges  
- 📊 **Reports** – withdrawals, deposits, and recalculated balances  

---

## 📂 Project Files
- `account.csv` – sample accounts dataset  
- `trnx.csv` – transfer instructions  
- `week14.sql` – schema, procedures, reports  
- `week14.pdf` – reference documentation  

---

## 🚀 How to Run

1. **Create database**
   ```sql
   CREATE DATABASE Bank;
   USE Bank;
