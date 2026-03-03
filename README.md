# 🛒 Retail Database Schema Design

This project features a complete SQL-based relational database design for a retail business. It includes the creation of master tables, transactional tables, and staging structures for data ingestion, demonstrating a solid understanding of database architecture and normalization.

## 📋 Key Features
- **Relational Schema:** Implementation of primary and foreign keys to ensure data integrity across Category, Product, Customer, and Store tables.
- **Transactional Logic:** Design of `sales_order` and `sales_order_line` tables to track complex retail transactions.
- **Data Warehousing Foundations:** Inclusion of staging tables (STG) with metadata fields like `ingestion_ts` and `batch_id`, following best practices for ETL/ELT processes.
- **Scalability:** Structured to handle multiple stores, employees, and diverse product categories.

## 🛠️ Tech Stack
- **SQL** (MySQL and Google BigQuery compatible syntax).
- **Database Design:** Relational Modeling (OLTP & Staging).

## 🗄️ Database Structure
The schema is divided into:
1. **Master Data:** Customers, Products, Stores, Categories, and Employees.
2. **Sales Data:** Order headers and line-item details.
3. **Staging Area:** Raw data tables for data integration and batch processing.

---
*Developed as a practical exercise in Database Management and SQL Engineering.*
