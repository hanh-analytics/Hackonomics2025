# 📁 Data

This folder contains datasets used in the **Hackonomics 2025** project:  
**High-Impact Financial Problem to Solve: _Predicting and Mitigating Financial Vulnerability Due to Climate Disasters_**

## 📌 Purpose
The datasets here support the analysis, modeling, and validation of our approach to predict financial vulnerability caused by climate-related disasters and develop strategies to mitigate economic impact on affected populations.

## 📊 Data Contents


| 🗂️ Data Type         | 📌 Source                                                                 | 📄 Notes                                                       |
|----------------------|---------------------------------------------------------------------------|----------------------------------------------------------------|
| 🏠 Housing + Income  | [U.S. Census Bureau](https://data.census.gov)                             | Median income, rent burden, % homeowners, education level      |
| 🌦️ Climate Risk      | [NOAA](https://www.ncei.noaa.gov) or [FEMA Disaster Declarations](https://www.fema.gov/openfema-data-page/disaster-declarations-summaries) | Frequency of floods, wildfires, hurricanes per region          |
| 🧾 Financial Stress   | [BEA](https://www.bea.gov/data), [Zillow Research](https://www.zillow.com/research/data/) | Optional: rent increases, inflation, cost-of-living indicators |

*Note: File names above are examples—replace or update based on your actual data files.*

## 🔐 Data Sensitivity
Ensure all datasets are either publicly available, properly licensed for use, or anonymized to comply with data privacy standards.

## 📂 Usage
These datasets are preprocessed and fed into our predictive pipeline found in the `notebooks/` and `models/` folders of the repository.

## ✅ Best Practices
- Keep raw data unmodified; use a separate folder for processed files (`data/processed/`)
- Document sources for each dataset in a `data_sources.md` file
- Include any relevant metadata or data dictionaries

---

_This project is part of the Hackonomics 2025 challenge, addressing global challenges through innovative data science solutions._
