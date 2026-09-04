# 🏨 Hotel Management System

A **Hotel Management System** developed as part of the **Database Management System Lab** at the **Institute of Space and Technology (IST), Islamabad**.

The system is designed to manage hotel operations including guests, rooms, bookings, billing, payments, employees, feedback, check-in/check-out, and room service requests through a structured relational database.

---

## 📌 Project Overview

The **Hotel Management System** is a database-driven application developed to organize and simplify common hotel management operations.

The system provides an admin-based workflow for managing:

* 👤 Guests
* 🏨 Rooms
* 📅 Bookings
* 💳 Billing
* 💰 Payments
* 👨‍💼 Employees
* ⭐ Customer Feedback
* ✅ Check-In / Check-Out
* 🛎️ Room Service Requests

The project demonstrates practical implementation of **SQL Server, relational database design, ERD, SQL queries, constraints, joins, aggregate functions, and frontend/backend connectivity**.

---

## ✨ Key Features

### 🔐 Admin Login System

The system provides secure administrator authentication through:

* Username verification
* Password verification
* Admin-only access

---

### 👤 Guest Management

The Guest Management module allows the administrator to:

* Add guest records
* Store guest personal information
* Manage guest contact details

---

### 🏨 Room Management

The Room Management module provides:

* Add new hotel rooms
* Different room categories
* Room availability status
* Room pricing management

---

### 📅 Booking Management

The Booking Management module handles:

* Room reservations
* Check-in dates
* Check-out dates
* Adult records
* Children records
* Booking status management

---

### 🧾 Billing System

The Billing module provides:

* Bill generation
* Payment status tracking
* Tax calculation
* Extra charges calculation
* Multiple payment methods

---

### 👨‍💼 Employee Management

The system manages hotel employee information including:

* Employee details
* Staff roles
* Salaries
* Shift timings

---

### 💳 Payment Management

A separate payment management system is implemented for:

* Maintaining payment records
* Tracking payment information

---

### ⭐ Customer Feedback System

Guests can provide feedback through the feedback system.

Features include:

* Feedback storage
* Rating system

---

### ✅ Check-In / Check-Out

The system tracks:

* Guest check-in
* Guest check-out
* Guest status

---

### 🛎️ Room Service Requests

The Room Service module allows the system to:

* Handle service requests
* Track request status

---

## 🗄️ Database Design

The project uses a **relational database design** with normalized tables and structured relationships.

The main entities represented in the ERD include:

* Guests
* Rooms
* Bookings
* Billing
* Payments
* Employees
* Feedback
* CheckInStatus
* RoomServiceRequests

The database uses **one-to-many relationships** where required.

---

## 🔑 Database Concepts Used

### Database Creation

```sql
CREATE DATABASE
USE DATABASE
```

### Table Creation

```sql
CREATE TABLE
```

### Primary Keys

Primary keys are used to uniquely identify records.

Examples:

* `GuestID`
* `RoomID`
* `BookingID`

### Foreign Keys

Foreign keys are used to establish relationships between tables.

Examples:

* `GuestID` in Bookings
* `RoomID` in Bookings
* `BookingID` in Billing

### Constraints

The project uses:

* `PRIMARY KEY`
* `FOREIGN KEY`
* `UNIQUE`
* `CHECK`
* `DEFAULT`
* `NOT NULL`

### Identity Property

```sql
IDENTITY(1,1)
```

is used for auto-increment functionality.

---

## 🧮 SQL Data Types

Different SQL Server data types are used, including:

* `INT`
* `VARCHAR`
* `DECIMAL`
* `DATE`
* `DATETIME`

---

## 📚 SQL Languages & Operations

### DDL — Data Definition Language

Used for:

* `CREATE DATABASE`
* `CREATE TABLE`

### DML — Data Manipulation Language

Used for:

* `INSERT`
* `UPDATE`
* `DELETE`

### DQL — Data Query Language

Used for:

* `SELECT`
* Filtering data
* Joining tables

---

## 🔗 SQL JOINs

The project uses:

### INNER JOIN

Used to combine data from multiple related tables.

---

## 📊 Aggregate Functions

The database uses aggregate functions including:

```sql
COUNT()
SUM()
MAX()
```

---

## ⚙️ Default Values

Default values are implemented using:

```sql
GETDATE()
```

as well as default status values.

---

## 🖥️ Technologies Used

| Technology        | Purpose                                   |
| ----------------- | ----------------------------------------- |
| **HTML**          | Frontend structure                        |
| **CSS**           | Styling and responsive design             |
| **JavaScript**    | Dynamic interactivity and UI improvements |
| **PHP**           | Server-side/backend connectivity          |
| **SQL Server**    | Database management                       |
| **SSMS**          | Query and database management             |
| **Visual Studio** | Frontend and backend development          |

The project uses PHP for connecting the application to the database, executing SQL queries, and handling data securely.

---

## 🔄 System Workflow

The implemented hotel management workflow is:

```text
Admin Login
     ↓
Guest Registration
     ↓
Room Allocation
     ↓
Booking Management
     ↓
Billing
     ↓
Payments
     ↓
Feedback Management
     ↓
Room Service Handling
```

This workflow represents the major operational flow of the Hotel Management System.

---

## 📂 Project Modules

```text
Hotel Management System
│
├── 🔐 Admin Login
│
├── 👤 Guest Management
│   ├── Add Guest
│   ├── View Guest
│   └── Manage Guest Information
│
├── 🏨 Room Management
│   ├── Add Room
│   ├── Room Categories
│   ├── Availability
│   └── Pricing
│
├── 📅 Booking Management
│   ├── Reservations
│   ├── Check-In
│   ├── Check-Out
│   └── Booking Status
│
├── 🧾 Billing
│   ├── Generate Bills
│   ├── Tax
│   └── Extra Charges
│
├── 💳 Payments
│   └── Payment Tracking
│
├── 👨‍💼 Employees
│   ├── Employee Information
│   ├── Roles
│   ├── Salaries
│   └── Shift Timings
│
├── ⭐ Feedback
│   └── Ratings
│
└── 🛎️ Room Services
    └── Service Request Tracking
```

---

## 🧪 Project Execution

The project was implemented and tested through different frontend operations, including adding and deleting records, adding guests/employees, adding rooms, completing services, and handling feedback.

Examples demonstrated in the project include:

* Room `104` added
* Guest record deleted
* Multiple employee records added
* Room `403` added
* Room service marked as completed
* Feedback functionality demonstrated

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Build a practical database-driven hotel management system
* Apply relational database concepts
* Design normalized database tables
* Implement primary and foreign key relationships
* Apply SQL constraints
* Perform CRUD operations
* Use SQL JOINs
* Use aggregate functions
* Connect frontend and backend
* Manage hotel-related records efficiently
* Understand practical implementation of DBMS concepts

---

## 👥 Team Members

### Team Leader

**Urneeb Zahra**
`251301002`

### Team Members

**M. Ahmed Bin Kashif Malik**
`251301047`

**Muhammad Saad Asghar**
`251301049`

### Submitted To

**Sir Osama Subhani Khan**

### Institute

**Institute of Space and Technology (IST)**
Islamabad, Pakistan

---

## 🎓 Academic Information

**Course:** Database Management System Lab
**Project:** Hotel Management System
**Group:** 07
**Institute:** Institute of Space and Technology, Islamabad

---

## 🚀 Future Improvements

Potential future improvements include:

* Online hotel room reservation
* Automated room availability updates
* Advanced booking search
* Customer accounts
* Online payment integration
* Email booking confirmations
* Advanced reporting and analytics
* Role-based access for hotel staff
* Improved dashboard with real-time statistics

---

## 📜 License

This project was developed for **academic and educational purposes** as part of the Database Management System Lab.

---

⭐ **Hotel Management System**
*An organized database-driven solution for managing hotel operations, bookings, billing, payments, guests, employees, and services.*
