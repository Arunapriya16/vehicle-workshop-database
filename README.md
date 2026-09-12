# Vehicle Workshop Database

## Project Description

The Vehicle Workshop Database is a MySQL database project designed to manage the operations of a vehicle workshop.

It stores information about companies, vehicles, employees, services, work assignments, quotations, and employee salaries.

## Technologies Used

* MySQL
* MySQL Workbench
* SQL

## Database Tables

The database contains 7 tables:

1. **Companies** – Stores company/customer details.
2. **Vehicles** – Stores vehicle information.
3. **Employees** – Stores workshop employee details.
4. **Services** – Stores available workshop services.
5. **Work Assignments** – Tracks services assigned to employees for vehicles.
6. **Quotations** – Stores service quotations for vehicles.
7. **Salaries** – Stores employee salary and payment details.

## Relationships

* Companies → Vehicles
* Vehicles → Work Assignments
* Employees → Work Assignments
* Services → Work Assignments
* Companies → Quotations
* Vehicles → Quotations
* Employees → Salaries

## SQL Concepts Used

* CREATE TABLE
* INSERT
* SELECT
* INNER JOIN
* WHERE
* ORDER BY
* GROUP BY
* HAVING
* Aggregate Functions
* LIKE
* BETWEEN
* Subqueries
* Foreign Keys

## How to Run the Project

1. Install MySQL Server and MySQL Workbench.
2. Open MySQL Workbench.
3. Create a new SQL tab.
4. Open the `vehicle_workshop_database.sql` file.
5. Execute the SQL script.
6. The database tables and sample data will be created.
7. Run the SQL queries to view and analyze the data.

## Project Structure

```text
vehicle-workshop-database/
│
├── vehicle_workshop_database.sql
└── README.md
```

## Author

Arunapriya S.
