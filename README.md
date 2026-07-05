# SQL Business Insights Project

A SQL analysis project that queries a relational business database to extract
insights on customers, orders, employees, suppliers, and products.

## Overview

The goal of this project is to analyze and manage business data across customers,
orders, employees, suppliers, and products. Through a series of SQL queries, the
project extracts insights that support informed decision-making, operational
optimization, and improved efficiency.

## Analysis Areas

### Customer Behavior

Identify the top 10 highest-spending customers and their purchasing patterns to
support targeted marketing and personalized promotions.

### Sales Performance

Analyze the top 5 purchased categories and their total cost to determine which
product categories drive revenue and to guide inventory and marketing strategy.

### Inventory Management

Find the most purchased items and their unit prices to inform stock levels and
ensure popular products remain available.

### Employee Management

List all employees in the Human Resources department with their full names to
support workforce planning and understand department composition.

### Supplier Analysis

Rank suppliers by total purchase cost to optimize procurement and strengthen key
supplier relationships.

### Product and Category Analysis

Review top categories, subcategories, product names, and unit prices for a
comprehensive view of product performance and market trends.

## Key Findings

- **Seasonal trends:** Sales performance varies across seasons and time periods.
  Recognizing these patterns supports better inventory planning and campaign
  timing.
- **Customer concentration:** A small share of customers accounts for a
  disproportionate portion of total revenue, a larger disparity than initially
  expected.
- The insights directly address the original research questions about customer
  behavior, sales drivers, and operational efficiency.

## Repository Contents

- `Script-SQLFINALPROJECT.db` — SQLite database used for the analysis
- `README.md` — project documentation

## How to Run

1. Clone the repository.
2. Open `Script-SQLFINALPROJECT.db` with a SQLite client such as DB Browser for
   SQLite, or connect to it from Python using the `sqlite3` module.
3. Run the analysis queries against the database tables.
