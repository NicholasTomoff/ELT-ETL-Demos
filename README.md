## ELT Example: PostgreSQL API → Google Sheets

This repository demonstrates a realistic ELT-style workflow using
Python-backed APIs, Google Sheets, and spreadsheet-based transformations.

The goal of this project is not to replicate proprietary enterprise work,
but to showcase approach, adaptability, and technical reasoning using
publicly accessible tools.

---

## Why this exists

My professional experience has primarily been built using Microsoft Excel,
SQL, and enterprise databases inside secured, company-managed environments.
That work cannot be shared due to intellectual property ownership.

This example was created specifically for portfolio purposes to demonstrate:
- How I approach data extraction and transformation
- Adaptability across tools and platforms
- Translating enterprise concepts into public, reproducible examples

---

## Workflow Overview (ELT Pattern)

1. **Extract**  
   Data is extracted from a live PostgreSQL-backed application via
   custom API endpoints.

2. **Load**  
   JSON responses are loaded into Google Sheets using Google Apps Script,
   creating structured, tabular datasets.

3. **Transform**  
   Transformations are performed directly in Google Sheets using:
   - Pivot tables
   - XLOOKUP
   - INDEX / MATCH
   - Spreadsheet-based business logic

---

## Key Notebook Walkthrough

📓 **`ETL_GoogleSheetsExample.ipynb`**

The notebook provides a step-by-step walkthrough covering:
- API-based data extraction
- Dynamic JSON parsing and flattening
- Automated loading into Google Sheets
- Spreadsheet-native transformation techniques

This mirrors how business users and analysts often interact with data
outside of traditional data warehouses.

---

## Technologies Used

- Python (API backend)
- PostgreSQL (data source)
- Google Sheets
- Google Apps Script (JavaScript)
- Spreadsheet transformation functions

---

## What this demonstrates

- Practical ELT patterns
- Spreadsheet automation and scripting
- Translation of Excel/VBA concepts into Google Apps Script
- Business-facing data transformation workflows
- Real-world constraints and tradeoffs

---

## Future Enhancements

- Refactor transformation logic into Python modules
- Add schema validation
- Load transformed data into a warehouse target
