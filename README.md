# Clinical Trials Database Management System

## Overview
This project implements a comprehensive database management system for clinical trials using SQLite. It provides a robust schema design, optimized queries, and advanced SQL features to efficiently manage and analyze clinical trial data.

## Key Features
- Relational database schema for studies, investigators, conditions, interventions, and organizations
- Optimized query performance using indexes, views, and Common Table Expressions (CTEs)
- Advanced SQL features including:
  - Triggers for soft deletions
  - Transaction management for data integrity
  - Complex JOIN operations for comprehensive trial reports

## Schema Design
The database includes tables for:
- Studies
- Investigators
- Conditions
- Interventions
- Organizations

Each table is designed with appropriate constraints and foreign key relationships to maintain data integrity and facilitate efficient querying.

## Optimization Techniques
- Strategic index creation for frequently queried columns
- Views for complex, frequently-used queries
- Common Table Expressions (CTEs) for improved query readability and performance

## Advanced Features
- Soft deletion mechanism using triggers
- Transaction management to ensure data consistency
- Comprehensive reporting capabilities using complex JOIN operations
