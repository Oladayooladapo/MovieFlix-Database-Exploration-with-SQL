
# MovieFlix Database Exploration with SQL  
### A Structured Analysis of Customer Behavior, Revenue, and Inventory Using SQL

---

## Business Background

**MovieFlix Rentals** is a leading DVD rental service offering a wide collection—from Hollywood hits to indie favourites. With a focus on **customer convenience**, MovieFlix provides flexible rental plans and a hybrid delivery model (online reservations + local pickup). To support smooth operations and data-driven decision-making, the business uses a relational database to track:

- Customers
- Movie inventory
- Rentals
- Payments
- Staff and store operations

---

## Problem Statement

MovieFlix's SQL database captures rich operational data across its rentals, payments, and customer behaviors. However, **insights need to be surfaced** through structured queries to guide key decisions.

This project aims to:
- **Understand** the schema and relationships within the database
- **Extract insights** on customer behavior, store performance, and rental trends
- **Answer business-critical questions** using optimized SQL queries

---

## Project Goals

- Showcase practical **SQL querying skills** across multiple table joins
- Demonstrate an ability to explore and analyze structured business data
- Provide value by answering real-world operational and strategic questions
- Translate raw data into **clear, actionable insights**

---

## Database Schema

The dataset consists of **16 interrelated tables**, forming a full transactional database:

actor, address, category, city, country, customer, film, film_actor, film_category, inventory, language, payment, rental, staff, store


Key Relationships:
- **Customers** rent **films** from a **store**
- Each **rental** has a corresponding **payment**
- Films are categorized and have **inventory** in stores
- **Staff** process rentals and payments
- **Geographic data** is available via city, address, country

---

## Tech Stack & SQL Concepts Used

- `SELECT`, `JOIN`, `GROUP BY`, `HAVING`, `ORDER BY`, `LIMIT`
- Aggregate functions: `COUNT()`, `SUM()`, `AVG()`
- Conditional logic: `CASE`, `WHERE`
- Subqueries and nested queries
- Data exploration with `DISTINCT`, `IS NULL`, `IN`

---

## Project Workflow

1. **Database Restoration**  
   Setup the MovieFlix SQL schema and populate it with sample data.

2. **Data Familiarization**  
   Review schema relationships and column meanings.

3. **Query Development**  
   Write queries to answer layered business questions.

4. **Insight Generation**  
   Translate query results into insights about inventory, revenue, and customer behavior.

---

## Business Questions Answered

### Movie Inventory Exploration

- Retrieve all movies in the database.
- List titles of movies with rental durations > 5 days.
- Find total number of movies.
- Count movies by rating (e.g., PG, R).

### Customer Rental Behavior

- Classify customers into **spending tiers** based on total payments.
- Identify the **top 10 most rented movies** and how often they were rented.
- Detect customers with **payments but no rentals** (data anomalies).

### Revenue and Payment Analysis

- Determine which **staff handled the most rentals** and how much revenue they generated.
- Calculate **average rental durations** by store.
- Analyze **store-level revenue**, and determine what percentage comes from **late fees**.

---

## Key Learnings

- Strong familiarity with normalized relational data and schema relationships
- Ability to use SQL for **analytical storytelling**
- Understanding of operational KPIs in a **retail entertainment business**
- Experience working with multi-table queries and joins for **real-world questions**

---

## What's Included in the Repository

| File/Folder | Description |
|-------------|-------------|
| `movieflix_dataset.sql` | Original database |
| `movieflix_exploration_queries.sql` | SQL queries written for analysis |
| `README.md` | Project documentation (this file) |
---

## Conclusion

This project demonstrates how SQL can be used to answer strategic business questions by tapping into the richness of relational data. It reflects my ability to structure complex queries, identify meaningful trends, and think like a business analyst within a technical environment.

