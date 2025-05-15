# 💰 Median Household Income Dataset – ACS 2023 5-Year Estimates

This dataset provides ZIP-level estimates of **median household income**, sourced from the **American Community Survey (ACS) 2023 5-Year Estimates**, specifically **Table B19013**. The data is inflation-adjusted to **2023 dollars** and is suitable for small-area financial vulnerability modeling.

---

## 📂 Files Included

| File Name | Description |
|-----------|-------------|
| `Income_Data.csv` | Main dataset with ZIP-level income estimates and margins of error |
| `Income_Metadata.csv` | Metadata file describing the variable codes (e.g., B19013_001E) |
| `Income_Table-Notes.txt` | Table notes from Census documentation for B19013 |

---

## 📑 Column Descriptions (`Income_Data.csv`)

| Column | Description |
|--------|-------------|
| `GEO_ID` | Unique geographic identifier (ZIP Code Tabulation Area, ZCTA) |
| `NAME` | Full name of the geographic area |
| `B19013_001E` | **Median household income (Estimate)** in 2023 inflation-adjusted dollars |
| `B19013_001M` | Margin of error for the estimate |
| `Geography` | ZIP Code Tabulation Area (ZCTA) |
| `Geographic Area Name` | Human-readable area name |
| `Estimate!!Median household income in the past 12 months (in 2023 inflation-adjusted dollars):` | Duplicate of B19013_001E (for readability) |

## 🧠 Suggested Usage

You can use this dataset to:
- Analyze income distribution across ZIP codes
- Merge with housing, education, FEMA, or NOAA climate risk datasets

## 📊 Data Source
- Table: B19013 – Median Household Income in the Past 12 Months

- Release: ACS 2023 5-Year Estimates

- Inflation Year: Adjusted to 2023 dollars

- Source: data.census.gov

## 📅 Update Cycle
- Reflects data collected from 2019–2023

- Updated annually with rolling 5-year averages for high geographic precision

## 📝 Notes
- Median income is used instead of mean to reduce the influence of outliers and better represent typical household earnings.

- Suitable for ZIP-level and small-area economic modeling.

- For trend analysis, consider comparing with previous ACS 5-Year releases.










