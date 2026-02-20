#  Library Management System – SQL Project (PostgreSQL)

---

##  Project Overview

This project simulates a real-world **Library Management System** built using PostgreSQL.

The goal was to design a relational database system and implement business logic using SQL, including automation through stored procedures and analytical reporting.

It demonstrates practical skills in database design, transactional logic, and operational reporting.

---

##  Database Design

The system includes the following core entities:

- Branches
- Employees
- Members
- Books
- Issued Status
- Return Status

The database enforces relational integrity using:

- Primary & Foreign Keys
- Constraints
- Controlled book availability logic

 ERD diagram included in the repository.

---

##  Key Features Implemented

###  1. Full CRUD Operations
- Insert new books and members
- Update member information
- Delete issued records
- Retrieve filtered datasets

###  2. Book Issuing System (Automation)
Created a stored procedure to:

- Check book availability
- Automatically update book status
- Insert issue record
- Prevent issuing unavailable books

###  3. Book Return System
Built a procedure that:

- Records return transactions
- Updates book availability
- Tracks return quality
- Prevents data inconsistency

---

##  Business & Analytical Queries

The project includes analytical SQL queries such as:

- Overdue book detection (30-day rule)
- Fine calculation system
- Branch-wise performance report
- Active members in last 2 months
- Employee productivity ranking
- Rental revenue by book category
- Books not yet returned

---

##  SQL Concepts Used

- INNER JOIN / LEFT JOIN
- GROUP BY & HAVING
- Common Table Expressions (CTE)
- CTAS (Create Table As Select)
- Date & Interval functions
- Stored Procedures (PL/pgSQL)
- Conditional logic (IF/ELSE)
- Aggregation functions
- Data integrity constraints

---

##  Sample Business Insight

- Identified overdue members and calculated fines at $0.50/day
- Ranked top-performing employees by number of processed issues
- Generated branch-level rental revenue reports
- Created summary tables for issued book frequency

---

##  Tools & Technologies

- PostgreSQL
- SQL
- PL/pgSQL
- Relational Database Modeling

---

##  Repository Structure

- `database_setup.sql` – Schema creation
- `procedures.sql` – Stored procedures
- `analysis_queries.sql` – Reporting queries
- `library_erd.png` – ERD diagram
- `sample_data/` – Data files

---

## 👤 Author

**Aamir Iqbal**  
Aspiring Data Analyst | SQL | PostgreSQL  

---

If you found this project interesting, feel free to connect or provide feedback!

---
