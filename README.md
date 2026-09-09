#  Swiggy Food Delivery Management System - SQL Practice Workbook

### Overview
This repository contains a comprehensive SQL script designed to create, populate, and query a relational database for a food delivery platform modeled after systems like Swiggy and Zomato. 

The primary objective of this project is to provide a robust practice environment for SQL learners, data analysts, and backend developers. It includes the complete database schema creation, mock data insertion for various entities, and a structured workbook of 150 SQL queries ranging from beginner to advanced levels.

### Database Schema
The database (`DeliveryDB`) consists of 9 interconnected tables designed to capture the end-to-end lifecycle of a food delivery order:

* **`Customers`**: Stores user demographic and registration details.
* **`Restaurants`**: Contains restaurant profiles, cuisines, ratings, and operating hours.
* **`MenuCategories` & `MenuItems`**: Manages the food catalog, categorization, pricing, and availability.
* **`Orders`**: The central transaction table linking customers, restaurants, and order amounts.
* **`DeliveryPartners` & `Delivery`**: Tracks logistics, assigned drivers, vehicle types, and exact delivery timelines.
* **`Payments`**: Logs transaction statuses, payment methods, and IDs.
* **`Reviews`**: Captures customer feedback for both food quality and delivery experience.

### SQL Practice Workbook Sections
The script includes 150 practice questions categorized systematically to build SQL proficiency step-by-step:

#### PART A: Beginner SQL (Questions 1–40)
*   **Concepts:** `SELECT`, `WHERE`, `ORDER BY`, `LIMIT`, `IN`, `BETWEEN`, `LIKE`, basic arithmetic operations, and aliasing.
*   **Focus:** Data retrieval, filtering, and basic sorting.

#### PART B: Aggregate Functions (Questions 41–60)
*   **Concepts:** `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`, `GROUP BY`, `HAVING`.
*   **Focus:** Summarizing data, finding statistical averages, and grouping records by categories.

#### PART C: JOIN Queries (Questions 61–90)
*   **Concepts:** `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, cross-table queries.
*   **Focus:** Retrieving related data across multiple normalized tables (e.g., generating consolidated order reports).

#### PART D: Date Functions (Questions 91–120)
*   **Concepts:** `CURRENT_DATE`, `YEAR`, `MONTH`, `DATEDIFF`, `TIMEDIFF`, `DATE_FORMAT`, `INTERVAL`.
*   **Focus:** Time-series analysis, calculating delivery durations, and generating daily/monthly business summaries.

#### PART E: Advanced SQL (Questions 121–150)
*   **Concepts:** Window Functions (`ROW_NUMBER`, `RANK`, `DENSE_RANK`, `NTILE`, `LAG`, `LEAD`), Common Table Expressions (CTEs), Subqueries, and Conditional Aggregation (`CASE WHEN`).
*   **Focus:** Ranking customers and restaurants, calculating running totals, moving averages, and generating executive KPI dashboards.

### How to Use

1. **Environment Setup:** Ensure you have a SQL environment set up (e.g., MySQL Workbench, phpMyAdmin, DBeaver, or a CLI).
2. **Execute Schema & Data:** Run the first section of the script to create the `DeliveryDB` database, build the tables, and insert the mock data.
3. **Practice:** Attempt to write the SQL queries for the 150 questions provided in the comments before looking at the provided solutions.
4. **Analyze:** Run the provided solutions in parts A through E to check your logic and understand advanced querying techniques.
