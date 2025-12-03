🍽 Restaurant Management System

A fully-featured desktop application for managing restaurant operations
(Orders, Stock, Employees, Tables, Roles, and More).

📌 Overview

Restaurant Management System is a full desktop solution built using C#, WinForms, 3-Tier Architecture, SQL Server, ADO.NET, and Windows Services.
It provides complete control over restaurant workflow including orders, meals, inventory, employees, permissions, bookings, and auditing.

This project simulates a real production system and follows clean, scalable, and maintainable architecture.


---

🚀 Features

🧾 Order & Customer Management

Create, update, and delete customer orders

Add meals to a cart and process payments

Auto-sync orders with database in real-time

Logging all user actions for auditing purposes


🍱 Menu & Ingredients Management

Full menu management

Every meal has specific ingredients

Ingredient stock deduction on each order

Handling insufficient stock via SQL transactions

Automatic rollback on failed operations


📦 Inventory Management

Real-time ingredient tracking

Low-stock detection

SQL Transaction-based stock validation

Secure and optimized stored procedures


👥 User Roles & Permissions

Multi-level user system

Each user role has custom permissions

Interface adapts dynamically (Enable/Visible)

Audit trail logging for all actions


🕒 Table Booking System

Schedule table reservations

Prevent double booking

Penalty rules for policy violations

Full booking history


🌳 Employee Hierarchy (TreeView)

Visual TreeView structure for employees

Recursive node generation

Role icons for easy identification


📊 Dashboard & Reports

Sales reports

Salary reports

Ingredient cost reports

Interactive charts


🔄 Windows Service

Automatic database backup every 30 minutes

Logs backup history


