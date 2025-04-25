# 🏦 Bank Management System

A simple SQL-based Bank Management System designed to manage customers, accounts, transactions, and loans. This project demonstrates the use of **MySQL** for creating relational database schemas, enforcing foreign key relationships, and performing basic operations related to banking.

---

## 📌 Objective

To build a mini banking system backend using SQL that allows:
- Customer management
- Account management
- Loan tracking
- Transaction handling

---

## 👥 Target Audience

- Students learning databases
- Beginners practicing SQL
- Recruiters reviewing SQL project experience

---

## 🛠️ Technologies Used

- **Database**: MySQL
- **SQL Features**: Tables, Foreign Keys, Constraints, Queries
- **Tools**: Git, GitHub (for version control)

---

## 🧱 ER Diagram

!![Screenshot 2025-04-26 010328](https://github.com/user-attachments/assets/e0c103b5-079d-4c05-b76c-75bcd8f01dd0)





> _Update with your ER diagram image file name if different_

---

## 🔧 Database Tables

### 1. `cus`
Stores customer information.

```sql
CREATE TABLE cus (
    cus_id INT PRIMARY KEY,
    cus_name VARCHAR(100),
    cus_mob_no BIGINT,
    cus_email VARCHAR(100),
    cus_address VARCHAR(100)
);
