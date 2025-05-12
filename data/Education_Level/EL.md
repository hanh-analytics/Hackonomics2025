# 📁 data

This folder contains Excel and CSV files sourced from the **U.S. Census Bureau**, focused on **educational attainment statistics** for the U.S. population, based on the **ACS 5-Year Estimates (2023)**.

## 📌 Data Overview

These datasets are used to assess educational vulnerability as a factor influencing financial resilience in the face of climate-related disasters. Educational attainment is a key indicator for understanding a population’s capacity to respond and recover from crises.

## 📂 File Structure

| Filename                             | Description                                                                 |
|--------------------------------------|-----------------------------------------------------------------------------|
| `Educational_Attainment_Data.csv`    | Cleaned ACS 5-Year (2023) estimates on education levels by geography       |
| `Educational_Attainment_Metadata.csv` | Metadata and data dictionary from the Census Bureau explaining variables   |

*Replace the filenames with the actual file names if different.*

## 🏛 Source

All files are sourced directly from the **U.S. Census Bureau**, specifically:
📎 [American Community Survey (ACS) Data](https://www.census.gov/programs-surveys/acs)

Relevant table(s) include:
- **Table S1501** – *Educational Attainment*

## ⚠️ Notes

- Data is broken down by geography (e.g., state, county), age group, and sex.
- Percentages reflect the proportion of the population 25 years and over with various levels of educational attainment.
- For complete definitions, refer to the accompanying metadata Excel file.

## ✅ Best Practices

- Keep raw downloads in `/data/raw/`
- Store cleaned and analysis-ready versions in `/data/processed/`
- Record any transformations or filters used during preprocessing in your workflow documentation

---

_This data supports analysis of population vulnerability from an education perspective within the Hackonomics 2025 challenge._
