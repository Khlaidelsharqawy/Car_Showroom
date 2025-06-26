# 🚗 Car Showroom SQL Database

A fully relational SQL-based database system for managing a car showroom, including customers, cars, employees, services, and modifications.

## 📋 Project Overview

This project simulates a real-world car showroom's operations with a focus on:

- Car inventory management
- Customer data and purchase history
- Employee and company hierarchy
- Service workshops and spare parts
- Car orders, modifications, and provisions

## 🧱 Tables Included

- `customers`, `Cutomers_phone`
- `car`, `carcolor`, `carorder`, `carprovision`
- `employee`, `employeephone`
- `company`, `work_shop`, `sparepart`
- `jop`, `modification`

## 🔧 Features

- Data creation using `CREATE TABLE`
- Sample data using `INSERT INTO`
- Business logic with `SELECT`, `UPDATE`, and `DELETE`
- Referential integrity with `FOREIGN KEY` constraints
- Query examples for analytics and updates

## 🗂 How to Use

1. Open your SQL environment (e.g., MySQL Workbench or SSMS).
2. Copy and run `Car_Showroom.sql` script.
3. Run SELECT queries to explore data.
4. Use provided updates to simulate business changes.

## 💡 Example Query

```sql
SELECT Brand, SUM(Quantity) AS Total_Stock
FROM car
GROUP BY Brand;
