# Snowflake Training Session Topics

## 1. Snowflake Introduction & Cloud Data Platform

### Topics

-   What is Snowflake?
-   Traditional Data Warehouse vs Cloud Data Warehouse
-   Snowflake Editions
-   Snowflake Cloud Platforms
-   Key Features of Snowflake
-   Snowflake Use Cases
-   Snowflake User Interface Overview
-   Account, Organization, Region, and Cloud Concepts

------------------------------------------------------------------------

## 2. Snowflake Architecture

### Topics

-   Overview of Snowflake Architecture
-   Storage Layer
-   Compute Layer
-   Cloud Services Layer
-   Multi-Cluster Shared Data Architecture
-   Separation of Storage and Compute
-   Metadata Management
-   Caching Architecture
-   Query Processing Flow

------------------------------------------------------------------------

## 3. Databases, Schemas, Tables & Views

### Topics

-   Creating Databases
-   Creating Schemas
-   Permanent Tables
-   Temporary Tables
-   Transient Tables
-   Standard Views
-   Secure Views
-   Materialized Views
-   Table and View Management
-   Basic DDL and DML Operations

------------------------------------------------------------------------

## 4. Virtual Warehouses & Compute Management

### Topics

-   What is a Virtual Warehouse?
-   Warehouse Sizes
-   Creating and Managing Warehouses
-   Auto-Suspend
-   Auto-Resume
-   Scaling Up vs Scaling Out
-   Multi-Cluster Warehouses
-   Warehouse Performance
-   Warehouse Monitoring
-   Adaptive Warehouses Overview

------------------------------------------------------------------------

## 5. Data Loading and Unloading

### Topics

-   Snowflake Data Loading Architecture
-   Bulk Data Loading
-   Continuous Data Loading
-   Loading Local Files
-   Loading Cloud Storage Files
-   COPY INTO Table
-   COPY INTO Location
-   Data Unloading
-   Load History and Error Handling

------------------------------------------------------------------------

## 6. File Formats, Stages & COPY INTO

### Topics

-   Named File Formats
-   CSV File Format
-   JSON File Format
-   Parquet File Format
-   Internal Stages
-   External Stages
-   User Stage
-   Table Stage
-   Named Stage
-   PUT and GET Commands
-   COPY INTO Command
-   Validation Mode

------------------------------------------------------------------------

## 7. Semi-Structured Data

### Topics

-   VARIANT Data Type
-   OBJECT Data Type
-   ARRAY Data Type
-   Loading JSON Data
-   Querying JSON Data
-   FLATTEN Function
-   LATERAL FLATTEN
-   Nested JSON Processing
-   Parquet Data Processing
-   XML Data Processing

------------------------------------------------------------------------

## 8. Micro-Partitions, Clustering & Query Pruning

### Topics

-   What are Micro-Partitions?
-   Automatic Partitioning
-   Columnar Storage
-   Micro-Partition Metadata
-   Query Pruning
-   Clustering Keys
-   Automatic Clustering
-   Clustering Information
-   Search Optimization Service
-   Performance Best Practices

------------------------------------------------------------------------

## 9. Time Travel, Fail-safe & Zero-Copy Cloning

### Topics

-   Snowflake Time Travel
-   Querying Historical Data
-   UNDROP Command
-   Data Retention Period
-   Fail-safe Concept
-   Time Travel vs Fail-safe
-   Zero-Copy Cloning
-   Database Cloning
-   Schema Cloning
-   Table Cloning
-   Development and Testing Use Cases

------------------------------------------------------------------------

## 10. Streams and Tasks

### Topics

-   Change Data Capture
-   Standard Streams
-   Append-Only Streams
-   Insert-Only Streams
-   Stream Metadata Columns
-   Creating Tasks
-   Task Scheduling
-   Task Dependencies
-   Task Graphs
-   Serverless Tasks
-   Streams and Tasks ETL Pipeline

------------------------------------------------------------------------

## 11. Dynamic Tables

### Topics

-   Introduction to Dynamic Tables
-   Dynamic Tables vs Streams and Tasks
-   Target Lag
-   Refresh Modes
-   Incremental Refresh
-   Full Refresh
-   Dynamic Table Dependencies
-   Monitoring Dynamic Tables
-   Dynamic Table Use Cases

------------------------------------------------------------------------

## 12. Snowpipe & Snowpipe Streaming

### Topics

-   Introduction to Snowpipe
-   Continuous Data Loading
-   Creating Pipes
-   AUTO_INGEST
-   Cloud Event Notifications
-   Snowpipe Monitoring
-   Snowpipe Cost Concepts
-   Snowpipe Streaming
-   Snowpipe vs COPY INTO
-   Real-Time Ingestion Architecture

------------------------------------------------------------------------

## 13. Secure Data Sharing & Marketplace

### Topics

-   Secure Data Sharing Architecture
-   Provider and Consumer Accounts
-   Creating Shares
-   Reader Accounts
-   Direct Sharing
-   Listing Concepts
-   Snowflake Marketplace
-   Cross-Region Sharing
-   Cross-Cloud Sharing
-   Secure Data Collaboration

------------------------------------------------------------------------

## 14. Roles, RBAC & Access Control

### Topics

-   Role-Based Access Control
-   System-Defined Roles
-   Custom Roles
-   Role Hierarchy
-   Object Ownership
-   Privileges and Grants
-   Future Grants
-   Managed Access Schemas
-   User Management
-   Service Users
-   Access Control Best Practices

------------------------------------------------------------------------

## 15. Query Performance Optimization

### Topics

-   Query Profile
-   Query History
-   Execution Plan Analysis
-   Partition Pruning
-   Warehouse Sizing
-   Caching
-   Result Cache
-   Warehouse Cache
-   Search Optimization Service
-   Query Acceleration Service
-   Clustering Optimization
-   Performance Troubleshooting

------------------------------------------------------------------------

## 16. Cost Monitoring & Resource Monitors

### Topics

-   Snowflake Credit Consumption
-   Compute Cost
-   Storage Cost
-   Cloud Services Cost
-   Warehouse Metering History
-   Query Attribution History
-   Resource Monitors
-   Credit Quotas
-   Alerts and Notifications
-   Budgets
-   Cost Optimization Best Practices

------------------------------------------------------------------------

## 17. Snowpark with Python

### Topics

-   Introduction to Snowpark
-   Snowpark Session
-   Snowpark DataFrames
-   Reading Snowflake Tables
-   DataFrame Transformations
-   Filtering and Aggregation
-   Joins
-   User-Defined Functions
-   Stored Procedures
-   Python Worksheets
-   Snowpark ML Introduction

------------------------------------------------------------------------

## 18. dbt with Snowflake

### Topics

-   Introduction to dbt
-   dbt Project Setup
-   Snowflake Connection Configuration
-   Sources
-   Models
-   Materializations
-   Views
-   Tables
-   Incremental Models
-   Seeds
-   Snapshots
-   Tests
-   Documentation
-   Macros and Jinja
-   dbt Deployment Workflow

------------------------------------------------------------------------

## 19. Cortex AI, Cortex Analyst & Cortex Search

### Topics

-   Introduction to Snowflake Cortex AI
-   Cortex AI Functions
-   COMPLETE Function
-   SUMMARIZE Function
-   SENTIMENT Function
-   TRANSLATE Function
-   EMBED Functions
-   Cortex Analyst
-   Semantic Models and Semantic Views
-   Natural Language to SQL
-   Cortex Search
-   Search Services
-   Retrieval-Augmented Generation Concepts
-   AI Application Use Cases

------------------------------------------------------------------------

## 20. Real-Time Snowflake Project / Hands-on Use Case

### Project Flow

-   Business Problem Definition
-   Source Data Analysis
-   Architecture Design
-   Database and Schema Creation
-   Stage and File Format Creation
-   Raw Data Loading
-   Data Cleaning and Transformation
-   Dimensional Data Modeling
-   Fact and Dimension Tables
-   Incremental Data Processing
-   Streams and Tasks Pipeline
-   Dynamic Tables
-   Data Quality Validation
-   Performance Optimization
-   Cost Monitoring
-   Security and RBAC
-   Dashboard Integration
-   Cortex AI Integration
-   Project Demo and Presentation

------------------------------------------------------------------------

# Suggested Practical Exercises

-   Create a Snowflake database and schema.
-   Create and configure a virtual warehouse.
-   Load CSV data from an internal stage.
-   Load JSON data and use FLATTEN.
-   Create standard, transient, and temporary tables.
-   Test Time Travel and UNDROP.
-   Create a zero-copy clone.
-   Build a CDC pipeline using Streams and Tasks.
-   Create a Dynamic Table.
-   Configure Snowpipe for continuous ingestion.
-   Create roles and grant privileges.
-   Analyze a slow query using Query Profile.
-   Create a Resource Monitor.
-   Build transformations using Snowpark Python.
-   Create a dbt model and test.
-   Build a simple Cortex AI use case.
-   Complete an end-to-end Snowflake data engineering project.
