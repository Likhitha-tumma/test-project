# SSIS ETL Project

## Project Overview

This project demonstrates an ETL (Extract, Transform, Load) process using SQL Server Integration Services (SSIS).

The project contains multiple SSIS packages for performing data extraction, transformation, and loading operations.

## Tools Used

- SQL Server
- SQL Server Management Studio (SSMS)
- SQL Server Integration Services (SSIS)
- Visual Studio
- GitHub

## SSIS Concepts Used

- Control Flow
- Data Flow
- Sequence Container
- Execute SQL Task
- Data Transformation
- Conditional Split
- Derived Column
- Data Conversion
- Merge Transformation
- Merge Join
- Row Count
- Connection Managers
- Master Package
- Precedence Constraints

## Project Structure

- `master.dtsx` - Main/master SSIS package
- Other `.dtsx` packages - Individual ETL processes
- Connection Managers - Database connections used by the packages

## ETL Process

1. Extract data from source
2. Transform and validate data
3. Apply required business rules
4. Load processed data into the destination
5. Execute packages through the master package

## Key Features

- Multiple SSIS packages
- Master package for package execution
- Sequence Containers
- Control Flow tasks
- Data Flow operations
- SQL Server integration

## Author

Likhitha Tumma
