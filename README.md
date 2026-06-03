# Exploratory Data Analysis (EDA) — Sales Dataset

A Python-based EDA project that analyzes a retail sales dataset to uncover insights on product performance, payment behavior, and monthly revenue trends.

---

## Project Overview

This notebook performs end-to-end exploratory data analysis on an Excel-based sales dataset. It covers data loading, cleaning, statistical analysis, and visualization — producing actionable business insights as output.

---

## Features

- **Data Loading & Inspection** — reads an Excel dataset and previews shape, columns, data types
- **Missing Value Handling** — detects and fills nulls (e.g., `CouponCode` → `"Unknown"`)
- **Summary Statistics** — mean, median, count, min, max for `TotalPrice`
- **Top Products by Revenue** — groups by product and sorts by total revenue
- **Payment Method Analysis** — frequency count of payment modes
- **Order Status Breakdown** — distribution of order statuses
- **Monthly Sales Trend** — extracts month from date and aggregates sales
- **Outlier Detection** — descriptive stats on `TotalPrice` to spot anomalies
- **Correlation Analysis** — numeric correlation matrix across all columns
- **Data Export** — saves the cleaned dataset as `cleaned_dataset.xlsx`

---

## Visualizations

| Chart | Description |
|---|---|
| Bar Chart | Top 5 products by revenue |
| Pie Chart | Payment method distribution |
| Line Chart | Monthly sales trend over time |

---

## Tech Stack

- Python 3.x
- pandas
- matplotlib
- openpyxl (for Excel I/O)

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/eda-sales-analysis.git
cd eda-sales-analysis
```

### 2. Install dependencies

```bash
pip install pandas matplotlib openpyxl
```

### 3. Add the dataset

Place your Excel file in the project root and rename it:

```
Dataset for Data Analytics (2).xlsx
```

### 4. Run the notebook

```bash
jupyter notebook EDA__main_file_.ipynb
```

---

## Output

- Printed summaries and statistics in the notebook cells
- Three inline visualizations (bar, pie, line)
- `cleaned_dataset.xlsx` — cleaned version of the original dataset saved to disk

---

## Key Insights

- Identifies **top-performing products** driving the most revenue
- Reveals **customer payment preferences** across available methods
- Tracks **monthly sales patterns** to spot seasonal trends or growth periods

---

## Project Structure

```
eda-sales-analysis/
│
├── EDA__main_file_.ipynb          # Main analysis notebook
├── Dataset for Data Analytics (2).xlsx   # Input dataset (add manually)
├── cleaned_dataset.xlsx           # Output: cleaned data (generated on run)
└── README.md
```

---

## Author

Khushnuma — BCA 6th Semester, Data Analytics Project
