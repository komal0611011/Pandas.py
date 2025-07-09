
# 🐼 Pandas Day 1 – Practice & Learning

This repository contains beginner-friendly practice code for Pandas Day 1, focused on building strong foundations for Data Engineering and Data Analysis.

## 📘 Topics Covered

- Creating Pandas **Series** from lists, tuples, strings
- Creating **DataFrames** from:
  - Dictionaries
  - Lists of lists
- Reading **CSV files** using `read_csv()`
- Exploring data using:
  - `.head()`, `.tail()`
  - `.shape`, `.columns`, `.dtypes`
  - `.info()`, `.describe()`

## 📂 Dataset Files Used

All CSV files used in this practice are placed inside the `datasets/` folder:

- `students.csv`
- `sales.csv`
- `courses.csv`
- `products.csv`

## ✅ How to Run

```bash
# No installation needed if Pandas is already installed

# Open the .py files in any IDE or run via terminal
python 01_series_basics.py


 Example

`python:

import pandas as pd
df = pd.Series([10, 20, 30])
print(df)




