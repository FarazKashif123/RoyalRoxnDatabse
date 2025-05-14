# RoyalRoxnDatabase

A fully normalized relational database system designed for the **Royal Roxn** management platform.

## 📌 Project Overview

This project demonstrates the design and implementation of a relational database that follows normalization techniques (1NF, 2NF, 3NF) to eliminate data redundancy and ensure data integrity.

## 🛠️ Features

- Fully normalized schema (1NF, 2NF, and 3NF)
- Designed for core business entities:
  - Departments & Employees
  - Vendors & Inventory
  - Management modules
- Avoids duplicate data by applying proper functional dependencies
- Implemented **Primary Keys** and **Foreign Keys** to maintain relationships
- Includes ERD and schema for major and subtype tables

## 🧩 Technologies Used

- SQL (MySQL / PostgreSQL / Oracle compatible)
- ERD tools (draw.io / Lucidchart, etc.)

## ✅ Normalization Levels Applied

- **1NF**: Removed multi-valued attributes and ensured atomicity  
- **2NF**: Removed partial dependencies by creating separate tables for composite keys  
- **3NF**: Removed transitive dependencies for cleaner relationships

## 🚀 How to Use

1. Clone the repository
2. Run the `create_tables.sql` script in your SQL database environment
3. Insert your sample data using `insert_sample_data.sql`
4. Review the ERD for understanding the structure and relationships

---

Let me know if you want me to include actual SQL code or ERD images, or if you're uploading this to a live database (like PostgreSQL or MySQL).



