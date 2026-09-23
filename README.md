SQL Mini Project 1: SQL Foundations & Database Operations

## Overview

This project practices basic SQL database operations by building a small `online_store` database. The script creates tables, inserts sample data, changes table structures, updates and deletes records, and uses a `CASE` expression to assign product price categories.

## Database

- **Database:** `online_store`
- **SQL file:** `Database Creation.sql`
- **SQL environment:** MySQL / MySQL Workbench

## What the script does

- Creates the `online_store` database and selects it for use.
- Creates `customers`, `products`, `orders`, and `orderdetails` tables.
- Inserts sample customer, product, order, and order-detail records.
- Adds an email column to `customers`, updates two customer emails, and deletes customer 102.
- Removes the `Address` column from `customers`.
- Renames the `orders.orderStatus` column to `Status`.
- Creates foreign-key relationships from `orderdetails` to `orders` and `products`.
- Uses `SELECT` to inspect table contents and filter customers by state.
- Uses `CASE` to label products as Budget, Standard, or Premium based on price.

## SQL concepts practiced

`CREATE DATABASE`, `USE`, `CREATE TABLE`, primary and foreign keys, `INSERT`, `SELECT`, `WHERE`, `ALTER TABLE`, `UPDATE`, `DELETE`, and `CASE`.

## Sample results

- The final customer table has 7 rows after customer 102 is deleted.
- The products, orders, and order details tables contain 5 sample rows each.
- Product price categories are calculated with `CASE` in the SQL script.

## Project files

- `Database Creation.sql` — database setup and project queries.
- `customers table.png` — customer query and result grid.
- `products table.png` — product query and result grid.
- `orders table.png` — order query and result grid.
- `order details table.png` — order-detail query and result grid.

## Run the project

Open `Database Creation.sql` in MySQL Workbench and execute the script in order. The script begins with `DROP DATABASE online_store`, which deletes an existing database with that name before recreating it. Run it only where replacing that database is intended.

## Notes

The screenshots show selected query results. The `.sql` file contains the full sequence of project statements
