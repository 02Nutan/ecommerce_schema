# 🛒 E-Commerce Database Schema

This project contains the SQL script and schema design for a simple **E-Commerce System**. It includes key entities like customers, products, orders, and payments — along with their relationships.

## 📁 Files Included

– SQL script to create the database tables
- ER Diagram – Visual representation of the schema

## 🧱 Schema Overview

### 🧾 Entities

- **Customer** – Stores customer information
- **Category** – Groups products into categories
- **Product** – Items for sale, linked to categories
- **Orders** – Stores order records for customers
- **OrderItem** – Junction table for orders and products
- **Payment** – Tracks payments for orders

### 🔗 Relationships

- A `Customer` can place many `Orders`
- A `Product` belongs to one `Category`
- An `Order` can include multiple `Products` via `OrderItem`
- Each `Order` has one `Payment`

## 🛠️ Tools Used

- MySQL Workbench 
- dbdiagram.io  for ER Diagram

## 💡 How to Use

1. Open the `.sql` file in MySQL Workbench or your preferred DB tool.
2. Execute the script to create the schema.
3. Insert sample data to test the relationships.
4. Modify as needed for your custom e-commerce system.

## ✅ Outcome

A **well-structured and normalized database schema** ready for use in an e-commerce application or for academic submission.

---

