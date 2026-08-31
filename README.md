<div align="Center">
  
# Marketing Campaign Data Quality & Cleaning Using Python
A complete Python data cleaning workflow for a messy marketing campaign dataset.

</div>

---

## **Project Overview** ##

This project demonstrates a complete Python data cleaning workflow for a messy marketing campaign dataset. The objective was to identify and correct common data quality issues before analysis, ensuring reliable and consistent data for business reporting and decision-making.

---

## **Business Problem** ##

Marketing datasets often contain inconsistent formatting, missing values, typographical errors, incorrect data types, duplicate columns, logical inconsistencies, and extreme values.

Poor data quality can lead to inaccurate reporting, unreliable business insights, and poor decision-making.

The objective of this project was to build a repeatable Python data cleaning pipeline that transforms messy marketing data into a clean, analysis-ready dataset.

---

## **Objectives** ##

- Standardize column names
- Clean monetary values
- Correct categorical inconsistencies
- Normalize Boolean variables
- Parse dates correctly
- Detect logical inconsistencies
- Handle duplicate columns
- Treat extreme outliers
- Extract useful features
- Produce an analysis-ready dataset

---

## **Dataset** ##

- Loaded Dataset: 2020 rows, 12 columns

[Marketing Campaign Dataset](Dataset/marketing_campaign_data_messy)

---

## **Tools Used** ##

Python

Pandas

NumPy

Regular Expressions

Datetime

---

## **Workflow** ##

Messy Dataset

↓

Data Assessment

↓

Cleaning Pipeline

↓

Validation

↓

Feature Engineering

↓

Analysis-Ready Dataset

---

## **Cleaning Process** ##

### Step 1 ###

**Header Standardization**

**Purpose**

Standardized column names by removing extra spaces, converting to lowercase, and replacing spaces with underscores to improve consistency.

### Step 2 ###

**Currency Cleaning**

**Purpose**

Removed currency symbols and converted the Spend column into numeric format for financial calculations.

### Step 3 ###

**Categorical Standardization**

**Purpose**

Corrected spelling mistakes and inconsistent channel names using mapping techniques.

### Step 4 ###

**Handling Mixed Booleans**

**Purpose**

To check for ongoing campaigns (True/False) instead of Yes, Y, 1, No

### Step 5 ###

**Date Parsing**

**Purpose**

For a correct Date Format

### Step 6 ###

**Logical Integrity (Clicks vs Impressions)**

**Purpose**

To check for errors i.e the total of ad popups should always be greater than clicks

### Step 7 ###

**Logical Integrity (Time Travel)**

**Purpose**

To check for input errors, campaigns usually lasts 30 days.

### Step 8 ###

**Feature Engineering**

**Purpose**

Extracted seasonal campaign information from campaign names to create a new analytical feature.

### Step 9 ###

**Cleaned Dataset**

**Purpose**

To provide a clean dataset ready for analysis.

---

## **Before and After** ##

| Data Quality Issue  | Status      |
| ------------------- | ----------- |
| Messy Headers       | ✅ Fixed     |
| Currency Symbols    | ✅ Fixed     |
| Wrong Data Types    | ✅ Fixed     |
| Boolean Values      | ✅ Fixed     |
| Duplicate Columns   | ✅ Removed   |
| Invalid Dates       | ✅ Fixed     |
| Outliers            | ✅ Treated   |
| Campaign Typos      | ✅ Fixed     |
| Feature Engineering | ✅ Completed |

---

## **Skills Demonstrated** ##

Python

Pandas

NumPy

Regex

Data Cleaning

Data Validation

Data Quality Assessment

Feature Engineering

Outlier Detection

Business Data Preparation

---

## **Repository Structure** ##

Marketing-Data-Quality-Cleaning/

│

├── README.md

├── Dataset/

│      marketing_campaign_data_messy.csv

├── Python/

│      Data_Cleaning.ipynb

├── Images/

└── Cleaned_Dataset/

│     marketing_campaign_data_cleaned.csv

---

## **Contact** ##

If you would like to discuss this project or connect professionally, feel free to reach out through my [GitHub profile](https://github.com/tanakamotsi03-glitch) or [LinkedIn](https://www.linkedin.com/in/tanaka-motsi-758139417/).

