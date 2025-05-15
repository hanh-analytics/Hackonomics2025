# 🏠 Homeownership Dataset (ACS 5-Year Estimates, 2023)

This folder contains data related to housing tenure from the **American Community Survey (ACS) 2018–2022 5-Year Estimates**, focusing on **owner-occupied vs renter-occupied housing units** across ZIP Code Tabulation Areas (ZCTAs) in the United States.

This data supports analysis for the Hackonomics 2025 project:  
**"Climate-Finance Risk Predictor"** — modeling financial vulnerability from climate shocks using socioeconomic indicators.

---

## 📁 Files Included

| File Name | Description |
|-----------|-------------|
| `Homeowners_Data.csv` | Cleaned dataset with housing tenure statistics by ZIP code (ZCTA) |
| `Homeowners_Metadata.csv` | Metadata mapping column codes to human-readable labels from ACS table **B25003** |
| `Homeowners_Table-Notes.txt` | Notes from the Census Bureau describing methodology, margins of error, and data definitions |

---

## 📊 Data Source

- **Table Code**: [B25003](https://data.census.gov/table?q=B25003&g=010XX00US&tid=ACSDT5Y2022.B25003)
- **Title**: Tenure (Owner- vs Renter-Occupied Housing Units)
- **Source**: United States Census Bureau, ACS 5-Year Estimates (2018–2022)

---

## 📑 Column Descriptions (`Homeowners_Data.csv`)

| Column | Description |
|--------|-------------|
| `GEO_ID` | Unique geographic identifier (ZIP Code Tabulation Area, ZCTA) |
| `NAME` | Full geographic name |
| `B25003_001E` | Total occupied housing units (Estimate) |
| `B25003_001M` | Margin of error for total housing units |
| `B25003_002E` | Owner-occupied housing units (Estimate) |
| `B25003_002M` | Margin of error for owner-occupied |
| `B25003_003E` | Renter-occupied housing units (Estimate) |
| `B25003_003M` | Margin of error for renter-occupied |
| `Geography` | ZIP Code Tabulation Area (ZCTA) |
| `Geographic Area Name` | Human-readable region name |

## 📊 Data Source
- Table: B25003 – Tenure

- Release: ACS 2023 5-Year Estimates

- Source: data.census.gov

## 🧾 Notes
- The margins of error (*_M) indicate 90% confidence intervals as per ACS methodology.

- ZCTA ≠ USPS ZIP Code, but approximates postal ZIP areas for demographic use.

## 📅 Update Cycle
- Data covers 2019–2023 and is updated annually with rolling 5-year averages.

