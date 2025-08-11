# Bunnings Synthetic Data Generation & Preprocessing in R

## Project Overview
This project was completed as part of the assessment at RMIT University.  
It simulates the role of a **data analyst** at **Bunnings Warehouse**, generating realistic synthetic datasets, introducing data imperfections, merging datasets, and performing preprocessing steps before summarising insights.

---

## Key Steps Performed
1. **Synthetic Data Creation**
   - Generated two datasets:
     - **Product Sales Data** – Contains product names, categories, prices, quantities, dates, and store locations.
     - **Customer Information Data** – Includes customer names, demographics, membership details, and purchase patterns.
   - Mixed data types: numeric, character, factor, and date.
   - Introduced correlated variables.
   - Added ~5% missing values in selected columns.

2. **Data Merging**
   - Merged datasets using a **common key** (CustomerID).
   - Retained variety in data types after merging.

3. **Data Type Inspection & Conversion**
   - Used `str()` to check structure.
   - Converted variables to factors, ordered factors, and relabeled levels where necessary.

4. **Summary Statistics**
   - Grouped by **Product Category**.
   - Calculated **mean**, **median**, **1st & 3rd quartiles**, and **standard deviation** for product prices.

5. **Missing Value Handling**
   - Identified missing data using scanning functions.
   - Applied **mean imputation** for numeric variables and **mode imputation** for categorical variables.

---
## Skills Demonstrated
- **R Programming** (`dplyr`, `magrittr`, `Hmisc`, `randomNames`)
- Data wrangling & preprocessing
- Synthetic data simulation
- Missing value handling
- Statistical summarisation
- Report generation using **R Markdown**

---
