# E-Commerce Database Management System

## Overview 

This project establishes an e-commerce database system. It employs R and RSQLite package to create, populate, validate, and query a SQLite database tailored for e-commerce operations. The system is designed to handle entities such as suppliers, products, inventory, customers, shipments, and payments, providing a comprehensive solution for e-commerce data management.

## Features

- **Database Creation and Schema Definition**: Constructs a database with tables for suppliers, products, inventory, customers, shipments, and payments. The schema is carefully designed to maintain referential integrity and support e-commerce operations.
- **Data Importation**: Incorporates an ETL (Extract, Transform, Load) process to import data from CSV files directly into the database, ensuring that the database is populated with real-world e-commerce data.
- **Data Validation and Integrity Checks**: Implements checks for duplicate customer records, products without categories, suppliers without contact information, payments linked to non-existent customers, and inventory items with negative stock levels.
- **Querying for Insights**: Executes a range of SQL queries to extract useful information such as total sales, most sold items, category-wise shipment analysis, customers with the highest spending, and inventory levels below the reorder threshold.
- **Advanced Analytics**: Performs advanced SQL queries to derive insights on the most and least popular product categories, top spending customers, and inventory management for maintaining optimal stock levels.

## How It Works

1. **Database Connection**: Establishes a connection to the SQLite database.
2. **Schema Creation**: Uses DDL (Data Definition Language) statements to create the necessary tables with appropriate constraints and relationships.
3. **Data Loading**: Reads data from CSV files and populates the database tables, overwriting existing data to ensure the database reflects the most current information.
4. **Data Validation**: Conducts checks to ensure data integrity and consistency across tables.
5. **Querying and Analysis**: Retrieves data using DQL (Data Query Language) to provide insights into various aspects of the e-commerce operation, from sales trends to inventory management.
6. **Database Disconnection**: Closes the connection to the database to ensure data integrity and release resources.

## Conclusion

This project delivers a comprehensive solution for e-commerce database management, leveraging R and RSQLite to handle complex data relationships and provide valuable insights into business operations.

