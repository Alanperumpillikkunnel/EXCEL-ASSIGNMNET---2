# EXCEL-ASSIGNMNET---2
Assignment submission 
# Excel Assignment 2: Data Cleaning and Transformation

## 📌 Project Overview
This project demonstrates advanced data cleaning, transformation, and formatting techniques using Microsoft Excel. The objective is to take a raw, messy dataset, clean inconsistencies, handle missing values, and prepare it for reliable data analysis.

---

## 🛠️ Tasks & Implementation Steps

### 1. Handling Missing Values
* **Price Column:** Identified missing values (e.g., *Sony Headphones*, *Coleman Camping Tent*, *Ray-Ban Sunglasses*) and proposed/implemented category-average imputation using Excel formulas (`AVERAGEIF`).
* **Category Column:** Identified blank entries (e.g., *Backpack*, *Sneakers*, *Fitness Tracker*) and imputed them based on product type and brand descriptions.

### 2. Correcting Inconsistent Data
* **Product Names:** Standardized casing variations (e.g., `laptop`, `smartphone`, `headphones`) to ensure text uniformity.
* **Category Typos:** Identified and corrected misspellings and truncated text (e.g., fixing `Electroni` to `Electronics`) using Excel's **Find and Replace** feature.

### 3. Removing Duplicates
* Checked the dataset for exact duplicate rows across all columns.
* Utilized Excel's **Remove Duplicates** tool under the *Data* tab to strip redundant rows.

### 4. Splitting and Merging Data
* **Split:** Extracted the **Manufacturing Date** and **Country Code** from the combined *Product ID* column (e.g., splitting `28-JAN-US` into date and country code).
* **Merge:** Combined the *Brand Name* and *Product Name* columns into a unified **Product Brand** column using the concatenation operator (`&`).

### 5. Number Formatting
* **Price:** Formatted numerical values into standard **Currency ($)** format.
* **Manufacturing Date:** Standardized dates into the `DD-MM-YYYY` custom format.

### 6. Conditional Formatting
* **Price Column:** Applied visual **Data Bars** to represent relative product prices dynamically.
* **Category Column:** Created a custom formula rule (`=F2="Electronics"`) to highlight all "Electronics" rows automatically.

---

## 📂 Files Included
* `Alan- Excel Assignment 2 - Data Cleaning and Transformation.xlsx`: The main workbook containing raw data, transformation steps, and applied formulas.
* `README.md`: Project documentation and workflow summary.

---
