# SQL - Joins & Relationships

## Introduction

In the previous project, you learned how to manipulate data within a single table using SQL. However, real-world systems rarely store all data in one place.

Instead, data is divided into multiple related tables, each representing a different entity (for example: users, products, orders).

In this project, you will learn how to:

- model relationships between tables
- understand how tables are connected using keys
- combine data from multiple tables using joins
- write more advanced queries using subqueries

This is a fundamental step toward working with real-world databases.


## Learning Objectives

By the end of this project, you should be able to:

- Understand relationships:
    - 1–1, 1–N, N–N
- Distinguish between:
    - primary key
    - foreign key
- Understand referential integrity (conceptually)
- Write queries using:
    - INNER JOIN
    - LEFT JOIN
    - CROSS JOIN
- Interpret NULL values in joins
- Work with junction tables
- Use subqueries in filtering and comparisons

## General Requirements

- Environment:
    - Ubuntu 20.04
    - SQLite 3.x
- Each task:
    - must be a .sql file
    - must contain a single query (unless stated otherwise)
- Execution:

```
sqlite3 library.db < file.sql
```

- Output must:
    - match expected results exactly
    - include explicit ORDER BY when needed
- Do not:
    - modify schema unless instructed
    - use unsupported SQL features