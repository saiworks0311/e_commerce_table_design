# # SQL for Data Analysis – E-Commerce Database

A hands-on SQL project built while learning and practicing SQL for Data Analysis using MySQL.

The project uses an e-commerce database to practice database creation, data manipulation, querying, filtering, aggregation, joins, subqueries, transactions, views, stored procedures, triggers, and other SQL concepts.

---

## 📌 Project Overview

This project was created as part of my SQL for Data Analysis learning journey.

The goal was to move beyond writing basic SQL queries and understand how SQL can be used to:

- Store and manage structured data
- Retrieve and filter information
- Analyze business data
- Calculate metrics and summaries
- Combine data from multiple tables
- Maintain data integrity
- Automate database operations

The main database used in the project is an **e-commerce database** containing customer orders, products, categories, pricing, order status, payment information, ratings, and seller information.

---

## 🛠️ Tools & Technologies

| Tool / Technology | Usage |
|---|---|
| MySQL | Database management system |
| MySQL Workbench | SQL development and database management |
| SQL | Data querying and analysis |
| CSV | Data import/export |
| Git & GitHub | Version control and project documentation |

---

## 🗄️ Database Structure

The project starts with an `ecom` database.

### Main Tables

#### `orders`

Stores information about customer orders.

| Column | Description |
|---|---|
| order_id | Unique order identifier |
| customer_name | Name of the customer |
| city | Customer city |
| product | Product ordered |
| category | Product category |
| quantity | Quantity purchased |
| price_per_unit | Price of one unit |
| discount_percent | Discount applied |
| order_date | Date the order was placed |
| delivery_date | Delivery date |
| payment_mode | Payment method |
| order_status | Current order status |
| rating | Customer rating |
| seller_id | Associated seller |

#### `sellers`

Stores seller information and is connected to the `orders` table using `seller_id`.

---

## 📊 Database Schema

![Database Schema](screenshots)

---

## 📚 SQL Concepts Practiced

### 1. Database & Table Creation

Created and used the `ecom` database and created tables using `CREATE DATABASE`, `CREATE TABLE`, and related SQL commands.

Example:

```sql
CREATE DATABASE ecom;

USE ecom;
