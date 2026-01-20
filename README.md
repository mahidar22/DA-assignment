# DA-assignment
bytexl DA assignment
# Flipkart Laptop Dataset (350 Rows)

## Overview
This dataset is a **synthetic Flipkart-style laptop product dataset** created for **data analysis, visualization, and academic projects**.  
It is fully compatible with the provided **FlipkartScraper analysis code** and does **not require live web scraping**.

The dataset simulates realistic pricing, ratings, and review distributions seen on Flipkart.

---

## File Information
- **Filename:** `flipkart_laptop_data_350_rows.csv`
- **Total Rows:** 350
- **Format:** CSV
- **Encoding:** UTF-8

---

## Columns Description

| Column Name | Data Type | Description |
|------------|----------|-------------|
| name | string | Laptop name including brand, model, and unique ID |
| price | float | Price of the laptop in INR |
| rating | float | Customer rating (3.5 – 5.0) |
| reviews | integer | Number of customer reviews |

---

## Brands Included
- HP  
- Dell  
- Lenovo  
- Asus  
- Acer  
- Apple  
- Samsung  
- MSI  

---

## Model Categories
- Pro  
- Elite  
- Gaming  
- Ultra  
- Premium  
- Business  
- Student  
- Thin  

---

## Data Characteristics
- Prices range between **₹25,000 and ₹1,60,000**
- Ratings are mildly correlated with price
- Review counts range from **20 to 6,000**
- Designed to produce meaningful:
  - Correlation analysis
  - Price-category segmentation
  - Visual analytics

---

## Usage Instructions

### Step 1: Place the CSV file
Move `flipkart_laptop_data_350_rows.csv` into your project directory.

### Step 2: Load the dataset
```python
import pandas as pd

df = pd.read_csv("flipkart_laptop_data_350_rows.csv")
```

### Step 3: Run analysis & visualization
```python
scraper.analyze_data(df)
scraper.visualize_data(df, "laptop")
```

---

## Suitable For
- Data Analytics projects
- Python + Pandas practice
- Matplotlib visualizations
- Academic submissions
- ML exploratory data analysis (EDA)

---

## Disclaimer
This is **synthetic data** generated for educational and demonstration purposes.  
It does not represent real Flipkart product listings.

---

## Author
Generated programmatically for analysis and visualization workflows.
