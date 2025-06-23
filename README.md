# 🛒 E-commerce Database Schema Design

## 📌 Overview

This project involves designing and implementing a relational database schema for a basic E-commerce platform. It includes SQL scripts for table creation and an ER (Entity-Relationship) diagram illustrating the relationships between entities.

## 📁 Files Included

- `ecommerce_schema.sql` – SQL script to create the database and tables
- `Ecommerce_ER_Diagram.pdf` – ER Diagram of the schema
- `README.md` – Project documentation

## 🧱 Database Tables

1. **Customer**
   - Stores customer details like name, email, and address.

2. **Category**
   - Represents product categories (e.g., electronics, fashion).

3. **Product**
   - Contains product information and links to categories.

4. **Order**
   - Records customer orders with order date and status.

5. **OrderItem**
   - Many-to-many relation between orders and products with quantity and price.

6. **Payment**
   - Stores payment details for each order.

## 🔗 Relationships

- One **customer** can place many **orders**.
- One **order** can contain many **products** (via `OrderItem`).
- One **product** belongs to one **category**.
- Each **order** has exactly one **payment**.

## 🧠 Key Concepts Covered

- DDL (Data Definition Language)
- Primary and Foreign Keys
- Composite Keys
- AUTO_INCREMENT usage
- Database Normalization
- ER Diagrams

## 🛠 Tools Used

- MySQL Workbench
- SQL
- GitHub
- ER Diagram Generator

## 🚀 How to Use

1. Import `ecommerce_schema.sql` into MySQL.
2. Use MySQL Workbench or any SQL tool to view the tables.
3. Open `Ecommerce_ER_Diagram.pdf` to view the database design.

## 📬 Contact

If you have any questions, feel free to reach out!
