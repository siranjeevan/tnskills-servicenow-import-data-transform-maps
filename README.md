# ServiceNow Data Import & Transformation using Transform Maps

## Project Overview

This project demonstrates an end-to-end data migration workflow in ServiceNow, where structured data from an external spreadsheet is imported, transformed, validated, and stored in a ServiceNow target table.

The project focuses on automating data ingestion using Import Sets and Transform Maps while maintaining data accuracy and avoiding duplicate records through Coalesce configuration. The imported information is then analyzed and presented using ServiceNow Reports and Dashboards.

## Repository Contents

### 📊 Sample Data Spreadsheet
Contains the source dataset used for the project. The spreadsheet includes sample employee information such as Employee ID, Name, Email, Department, and Location.

### ⚙️ ServiceNow Update Set
Contains the exported ServiceNow configurations created during the project, including:

- Custom target tables
- Import Set configurations
- Transform Maps
- Field mappings
- Coalesce configuration
- Reports
- Dashboard components

## Project Implementation

### 1. Source Data & Target Table Setup
Created a structured spreadsheet containing sample employee records and designed the corresponding target table in ServiceNow to store the imported information.

### 2. Import Set & Transform Map Configuration
Configured an Import Set Table to act as a staging area for the external spreadsheet data. A Transform Map was then created to establish relationships between source columns and ServiceNow target fields.

### 3. Data Transformation & Validation
Executed the transformation process and verified that the imported records were correctly mapped and stored in the target table. Data validation was performed to ensure consistency and accuracy throughout the migration process.

### 4. Duplicate Prevention with Coalesce
Configured Coalesce on the appropriate field to uniquely identify existing records. This ensures that matching records are updated instead of creating unnecessary duplicate entries during subsequent imports.

### 5. Reports & Dashboard
Created ServiceNow Reports to analyze and present the imported data. The reports were organized into a dashboard to provide a centralized and easy-to-understand view of the resulting records.

## Key ServiceNow Concepts Demonstrated

- Import Sets
- Import Set Tables
- Transform Maps
- Field Mapping
- Data Transformation
- Coalesce
- Data Validation
- Custom Tables
- ServiceNow Reports
- ServiceNow Dashboards
- Update Sets

## Project Outcome

The completed workflow provides a reusable approach for importing spreadsheet-based data into ServiceNow. It demonstrates how external data can be systematically processed, transformed, validated, and visualized while maintaining data integrity and minimizing duplicate records.
