# Hackonomics2025
A machine learning-powered dashboard that predicts financial vulnerability to climate disasters across U.S. communities. Built for Hackonomics 2025, this project combines economic modeling, environmental data, and interactive visualizations to help policymakers and individuals prepare for the financial risks of climate change.

# 🌍 Climate Vulnerability Predictor


## 💡 Solution

We built a machine learning model that uses real-world data to **predict financial vulnerability to climate events** at the zip code level, and visualized it through an interactive dashboard.  
Our project empowers:
- **Households** to understand their risk exposure
- **Policymakers & nonprofits** to prioritize resilience funding and outreach
- **Educators** to teach climate finance using live, localized data

---

## 🛠️ Tech Stack

| Layer | Tools |
|-------|-------|
| **Languages** | Python, SQL |
| **Libraries** | Pandas, NumPy, scikit-learn, XGBoost |
| **Visualization** | Plotly Dash, Tableau |
| **Data Sources** | NOAA API, FEMA Disaster Declarations, U.S. Census, Zillow API |
| **Platform (optional)** | Streamlit / Heroku for deployment |

---

## 🧠 How It Works

1. **Data Ingestion**: Pulled regional weather events, housing data, and socioeconomic indicators from multiple APIs and datasets.
2. **Preprocessing**: Cleaned and joined datasets on ZIP codes; handled missing data; scaled key features.
3. **Modeling**: Trained Random Forest and Gradient Boosting models to predict financial vulnerability scores.
4. **Visualization**: Displayed results in a user-friendly dashboard with maps and filterable metrics.
5. **Education**: Embedded tooltips and a “Learn” section to explain key financial literacy concepts (e.g., asset exposure, disaster risk, housing cost burden).

---

## 📊 Screenshots

> *Insert your screenshots or demo GIFs here — Dash app map, risk chart, feature importance plot, etc.*

---

## 🎥 Demo Video

Watch the full walkthrough here → [Insert YouTube or Google Drive link]

---

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/climate-finance-risk-predictor.git
   cd climate-finance-risk-predictor

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
3. Run the app:
   ```bash
   python app.py
Alternatively, open `notebooks/model_pipeline.ipynb` to explore the data and model interactively.

## 🌱 Future Directions
- Incorporate real-time disaster feeds
- Build mobile-first interface for community access
- Partner with local nonprofits for pilot deployment
- Add AI explanations (e.g., SHAP values) to explain predictions

## 🧠 Team
This project was created by:

Hanh Le (Applied Mathematics, UMass Boston)

## 📄 License:
