# 🎵 Music Store Management System (SQL Project)

##  Project Overview

The **Music Store Management System** is a relational database project designed to manage and analyze a digital music store.
It demonstrates strong fundamentals of **database design, normalization, SQL querying, and business analytics** using real-world scenarios.

This project helps extract meaningful insights about customers, sales, music preferences, and revenue trends.

---

##  Database Schema

The database consists of **10+ interconnected tables**, including:

* **Genre** – Music categories
* **MediaType** – Music formats
* **Employee** – Staff details and hierarchy
* **Customer** – Customer information and support reps
* **Artist** – Music artists
* **Album** – Artist albums
* **Track** – Songs with pricing, genre, duration
* **Invoice** – Purchase transactions
* **InvoiceLine** – Detailed purchase items
* **Playlist & PlaylistTrack** – User playlists

All tables are linked using **primary and foreign keys** to ensure data integrity.

---

##  Data Handling

* Created and managed database schema using **MySQL**
* Imported bulk data using **CSV files**
* Enforced referential integrity with foreign key constraints

---

##  Business Questions Solved

The project answers key analytical questions such as:

1. Who is the **senior-most employee**?
2. Which **countries generate the most invoices**?
3. What are the **top 3 invoice values**?
4. Which **city generates the highest revenue**?
5. Who is the **best customer** overall?
6. Who are the **Rock music listeners**?
7. Which artists have the **most Rock tracks**?
8. Which tracks are **longer than average**?
9. How much does each customer spend on each artist?
10. What is the **most popular genre per country**?
11. Who is the **top customer in each country**?

---

##  Skills & Concepts Used

* SQL (MySQL)
* Database Design & Normalization
* JOINs, Subqueries, Aggregations
* Window Functions (`RANK`)
* Data Analysis & Business Insights
* CSV Data Import

---

##  How to Run the Project

1. Create the database:

   ```sql
   CREATE DATABASE music;
   USE music;
   ```
2. Run the provided SQL file to create tables.
3. Import CSV files using `LOAD DATA INFILE`.
4. Execute analytical queries to explore insights.

---

##  Key Learnings

* Designing scalable relational databases
* Writing optimized SQL queries for analytics
* Translating business questions into SQL solutions
* Working with real-world structured data

---

##  Future Enhancements

* Add indexes for performance optimization
* Create views for reusable analytics
* Integrate with a BI dashboard (Power BI / Tableau)
* Extend the schema for streaming analytics

---

⭐ If you found this project helpful, don’t forget to **star the repository**!

---


