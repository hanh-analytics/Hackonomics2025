# 🏘️ Rent Burden Dataset – ACS 2023 5-Year Estimates

This dataset contains ZIP-level estimates of **rent burden**, defined as the percentage of households spending **more than 30% of their income on rent**. Data is sourced from the **American Community Survey (ACS) 2023 5-Year Estimates**, using **Table B25070**.

This metric is critical in assessing housing affordability and financial vulnerability.

---

## 📂 Files Included

| File Name | Description |
|-----------|-------------|
| `RentBurden_Data.csv` | Main dataset with rent categories by ZIP |
| `RentBurden_Metadata.csv` | Metadata file describing each column code (e.g., B25070_007E) |
| `RentBurden_Table-Notes.txt` | Table notes and definitions from ACS Table B25070 |

---

## 📑 Column Descriptions (`RentBurden_Data.csv`)

| Column | Description |
|--------|-------------|
| `GEO_ID` | Unique geographic identifier (ZIP Code Tabulation Area, ZCTA) |
| `NAME` | Full name of the geographic area |
| `B25070_001E` | Total renter-occupied households with cash rent (Estimate) |
| `B25070_007E` → `B25070_010E` | Count of households paying >30% of income on rent |
| `Geography` | ZIP Code Tabulation Area (ZCTA) |
| `Geographic Area Name` | Human-readable ZIP area name |
| `Estimate!!30.0 to 34.9%` → `Estimate!!50.0% or more` | Human-readable rent burden brackets |

> ⚠️ Note: Margins of error (columns ending in `M`) are also available for all estimates.

---

## 🧠 How Rent Burden Is Calculated

To compute the **percentage of rent-burdened households** in a ZIP code:
```python
burdened_cols = [
    'B25070_007E', 'B25070_008E', 'B25070_009E', 'B25070_010E'
]
df['pct_rent_burdened'] = df[burdened_cols].sum(axis=1) / df['B25070_001E'] * 100

## 📊 Data Source
- Table: B25070 – Gross Rent as a Percentage of Household Income

- Release: ACS 2023 5-Year Estimates

- Source: data.census.gov

## 📝 Notes
- ZCTA approximates USPS ZIP codes for demographic analysis.

- This dataset reflects data collected from 2019–2023.

- Margins of error should be considered when analyzing ZIPs with small renter populations.

## 🔍 Suggested Use Cases
- Quantify housing affordability across ZIP codes

- Merge with income, education, and climate risk data

- Use pct_rent_burdened as a feature in a financial vulnerability index
