# SQL - CRUD Operations

## Introduction

In this project, you will begin working with SQL (Structured Query Language) and the relational model, which together form the foundation of most modern data systems.

A relational database organizes data into tables (also called relations). Each table consists of:

- Rows (records): individual entries
- Columns (fields): attributes describing each record

For example, a table of books may include columns such as title, author, and price, where each row represents a single book.

SQL is the language used to define, query, and manipulate this data. It allows you to:

- insert new data
- retrieve existing data
- update records
- delete records

These operations are commonly referred to as CRUD:

- Create → INSERT
- Read → SELECT
- Update → UPDATE
- Delete → DELETE

This project introduces these operations using a single table, allowing you to focus on how SQL works before dealing with relationships between tables.

## Learning Objectives

By the end of this project, you should be able to:

- Understand the relational model (tables, rows, columns)
- Write SQL queries using standard syntax
- Perform CRUD operations:
- INSERT
- SELECT
- UPDATE
- DELETE
- Filter data using WHERE
- Select specific columns
- Sort results using ORDER BY
- Limit results using LIMIT
- Use aggregate functions:
- COUNT, SUM, AVG, MIN, MAX
- Group data using GROUP BY
- Interpret query results correctly

## General Requirements

- Environment used for correction:
- Ubuntu 20.04
- SQLite 3.x (CLI)
- Each task must be written in a .sql file
- Each task must use:
- one SQL query only, unless stated otherwise
- Queries must be executable using:
`  sqlite3 books.db < file.sql`
- Output must:
- match exactly the expected result
- include correct column order
- include correct row order when required
- If ordering is required, you must use:
`  ORDER BY`
- Do not:
- modify table structure unless explicitly instructed
- use joins or subqueries
- use non-standard SQL unless explicitly allowed