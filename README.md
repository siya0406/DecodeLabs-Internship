# Data Analytics Internship — Decodlabs

## 📌 Project Overview
This repository documents my end-to-end data analytics workflow during my internship at Decodlabs. The project transitions a raw corporate transactional dataset of 1,180+ records through rigorous data cleaning into an optimization-ready business intelligence resource.

---

## 🧹 Week 1: Data Cleaning & Preparation

### Objective
Process a messy, unformatted corporate dataset to ensure data integrity, structural consistency, and accuracy for downstream calculations.

### Fixes Performed
*   **Missing Values Handling:** Swept the dataset for blank cells. Standardized optional attributes (e.g., filling 305 missing instances in `CouponCode`) with `'N/A'` to prevent systemic downstream null errors.
*   **Data Deduplication:** Screened for and purged redundant records, establishing a reliable baseline of unique transaction keys (`OrderID`).
*   **Formatting & Logic Alignment:** Standardized inconsistent text casing across text entries, removed trailing white spaces using advanced text functions, and structured date strings.

<img width="1913" height="1016" alt="Data Preparation Step" src="https://github.com/user-attachments/assets/3aecdaf7-5c89-4e25-86b0-7baf21a3ee2e" />

---

## 📊 Week 2: Exploratory Data Analysis (EDA)

### Objective
Leverage the cleaned dataset to identify core business trends, calculate baseline descriptive statistics, isolate transactional outliers, and deliver actionable insights.

### Key Deliverables & Methodologies
1.  **Descriptive Statistical Profiling:** Extracted foundational metrics (Count, Mean, Median) across core financial columns including `TotalPrice`, `Quantity`, `UnitPrice`, and `ItemsInCart`.
2.  **Trend Mapping via Pivot Architecture:** Formulated high-level Pivot Tables and Pivot Charts to visualize product category revenue and digital acquisition funnels.

### Key Business Insights Captured
*   **Core Revenue Drivers:** Physical assets like `Chair` and `Printer` segments generated the maximum total sales share, indicating robust commercial demand.
*   **Optimal Marketing Channels:** Digital traffic funneling through `Instagram` emerged as the highest-performing customer pipeline, with targeted `Email` campaigns trailing as a close second.
*   **Consumer Checkout Habits:** Digital transactional formats (Online/Card options) dominate standard checkouts over cash processing, suggesting a strategic opportunity for gateway-specific promotion incentives.

---

## 🛠️ Tech Stack & Tools Used
*   **Microsoft Excel:** Advanced Formulas (`AVERAGE`, `MEDIAN`, `COUNT`, text functions), Conditional Formatting, Pivot Tables, and Pivot Charts.
