# Library Management System (MySQL)

This project implements a complete relational database to manage a library's books, authors, members, and loans.

## Features
- Tracks books, authors, and genres
- Manages members who borrow books
- Records book loans and return dates
- Implements relationships: 
  - One-to-Many (Authors → Books, Members → Loans)
  - Many-to-Many (Books ↔ Genres)

---

## How to Run the Project

1. Install MySQL (if not already installed)
2. Clone or download this repo
3. Open MySQL Workbench or your preferred MySQL client
4. Run the `library.sql` script to create the database and all tables

```sql
SOURCE path/to/library.sql;

# FINALPROJECTANDDEPLOYMENTSQL
