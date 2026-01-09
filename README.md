# Excel for Data Analysis

## Overview
This repository contains Excel-based data analysis and data transformation projects demonstrating practical skills commonly used in **Business Intelligence, Data Analytics, and Business Operations** roles.

The projects focus on transforming raw and semi-structured data into **clean, normalized, and analysis-ready datasets** using Microsoft Excel. Emphasis is placed on data preparation, lookup-based integration, string manipulation, and pivot-driven analysis rather than visualization alone.

---

## Objectives
The purpose of this repository is to showcase the ability to:
- Clean and normalize data for consistent analysis
- Integrate multiple datasets using lookup keys
- Perform text parsing and string manipulation
- Apply Excel formulas to support analytical workflows
- Build structured, analysis-ready outputs suitable for reporting

---

## Projects Included

### 1. Address Lookup & Census Data Transformation
**File:** `Address_lookup.xlsx`

This project involves transforming and integrating large U.S. Census Block Group (CBG) datasets into a single, structured Excel workbook. Multiple source tables were combined using lookup keys and Excel formulas to create an analysis-ready dataset.

**Key work performed:**
- Integrated multiple census datasets into a single workbook
- Cleaned and normalized Census Block Group (CBG) identifiers across all tabs to maintain consistent lookup keys
- Used helper columns with Excel text functions to standardize formats
- Enriched geographic data using FIPS codes and state lookup tables
- Built a consolidated submission template using nested formulas (no hidden columns)
- Created pivot tables for state-level demographic and income analysis
- Answered analytical questions using Excel formulas and `GETPIVOTDATA`

**Skills demonstrated:**
- Data normalization and standardization
- Lookup-based data integration
- Nested Excel formulas
- Pivot table analysis
- Analytical reasoning using structured data

---

### 2. String Manipulation & Data Cleaning
**File:** `String_Manupulation.xlsx`

This project focuses on text transformation and parsing tasks that are commonly required during data cleaning and preprocessing stages of analytics workflows.

**Key work performed:**
- Parsed first and last names from text fields
- Applied correct use of relative and absolute cell references
- Used lookup functions to enrich tabular data
- Performed conditional aggregation using `SUMIFS`
- Counted words using helper columns
- Parsed URLs to extract domain names and parameters
- Used helper columns where appropriate to simplify complex formulas

**Skills demonstrated:**
- String manipulation and text normalization
- URL parsing and domain extraction
- Lookup functions (`VLOOKUP`)
- Conditional aggregation
- Structured and readable formula design

---

## Excel Functions & Techniques Used
- `LEFT`, `RIGHT`, `MID`, `LEN`
- `SEARCH`, `FIND`
- `TRIM`, `CLEAN`
- `IF`
- `VLOOKUP`
- `SUMIF`, `COUNTIF`, `SUMIFS`
- `GETPIVOTDATA`
- Absolute and relative references
- Helper columns for complex transformations

---

## Data Preparation Approach
- Raw identifiers were cleaned and normalized to ensure consistent lookup keys across datasets
- Helper columns were used selectively to simplify complex string and parsing logic
- Final output sheets were kept clean and analysis-ready, with transformation logic isolated where appropriate

---

## Data Availability & Repository Scope
Raw source CSV files used in the Address Lookup project were intentionally **not included** in this repository due to their large size (exceeding **1 GB** in total).

The repository contains only the **final cleaned, transformed, and analysis-ready Excel workbooks** to focus on:
- Transformation logic
- Analytical techniques
- Final outputs rather than raw storage

---

## Tools
- Microsoft Excel

---

## Intended Audience
This repository is intended to demonstrate Excel-based data analysis skills relevant to:
- Business Intelligence
- Data Analytics
- Business Operations
- Data Engineering foundations

---

## Notes
These projects emphasize **data preparation and transformation**, reflecting real-world analytics workflows where data cleaning and integration often represent the majority of the effort.

