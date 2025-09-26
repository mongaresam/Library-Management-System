# 📚 Library Management Database

This project implements a **Library Management System** using **MySQL**.
It demonstrates relational database design with well-structured tables, constraints, and relationships.

---

## 🚀 Features

* Manage **Members** who borrow books
* Manage **Authors** and their books
* Manage **Books** (linked to authors and categories)
* Track **Loans** (who borrowed which book and when)
* Organize books into **Categories** (many-to-many relationship)

---

## 🗂 Database Schema

* **Members** → Library members (borrowers)
* **Authors** → Book authors
* **Books** → Library books (with ISBN and publication year)
* **Loans** → Records of borrowed and returned books
* **Categories** → Book genres (e.g., Fiction, Science, History)
* **BookCategories** → Junction table for many-to-many relationship between Books and Categories

---

## 🔑 Relationships

* **One-to-Many**: Authors → Books
* **One-to-Many**: Members → Loans
* **Many-to-Many**: Books ↔ Categories

---

## ⚙️ Setup Instructions

### 1. Clone the project

```bash
git clone <your-repo-url>
cd library-data
```
# Library-Management-System
