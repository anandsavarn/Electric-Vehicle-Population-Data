<div align="center">

<!-- HEADER BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:003300,100:006600&height=200&section=header&text=Electric%20Vehicle%20Population%20Analysis&fontSize=32&fontColor=00ff88&fontAlignY=38&desc=Data%20Analytics%20%7C%20Excel%20%7C%20Power%20BI%20%7C%20Python&descAlignY=58&descColor=88ffcc&animation=fadeIn" width="100%"/>

<br/>

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

<br/>

> **Uncovering EV adoption trends, geographic patterns, and manufacturer dominance through end-to-end data analysis — from raw government data to interactive dashboards.**

<br/>

[![Dataset](https://img.shields.io/badge/📂%20Data%20Source-data.gov-1a73e8?style=for-the-badge&logo=googledrive&logoColor=white)](https://catalog.data.gov/dataset/electric-vehicle-population-data)
[![Portfolio](https://img.shields.io/badge/🌐%20Portfolio-anandsavarn.vercel.app-00C896?style=for-the-badge)](https://anandsavarn.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-Anandsavran-181717?style=for-the-badge&logo=github)](https://github.com/Anandsavran)

</div>

---

## 📸 Dashboard Preview

<div align="center">
<img src="https://drive.google.com/file/d/1YHVE9dyBJqn3ZPNCDNKfggP-uYu0E9Qd/view?usp=drive_link" alt="Electric Vehicle Population Dashboard" width="95%"/>

> *Interactive dashboard showing EV growth trends, geographic distribution, manufacturer rankings, and vehicle type breakdown across US states.*
</div>

---

## 📘 Project Overview

The **Electric Vehicle Population Data Analysis** project investigates real-world EV registration data sourced from the **US government open data portal**. Using Excel for structured analysis and Power BI for interactive visualization, the project maps the story of EV adoption across American states — revealing who's driving it, where, and why.

This project serves as a decision-support tool for **policymakers, EV manufacturers, and urban planners** looking to understand the momentum behind electric mobility.

---

## 🎯 Key Objectives

| # | Objective | Technique Used |
|---|---|---|
| 1 | 🧹 Data Cleaning & Preprocessing | Power Query, Pandas |
| 2 | 📈 EV Growth Trend Analysis | Line Charts, Year-over-Year |
| 3 | 🌍 Geographic Distribution Mapping | Filled Map, Folium |
| 4 | 🚗 Manufacturer & Model Dominance | Ranked Bar Charts |
| 5 | ⚡ Electric Range vs Model Year | Scatter Plot, Correlation |
| 6 | 🔌 BEV vs PHEV Breakdown | Donut Chart, Segmentation |

---

## 🧰 Tech Stack

```
📊 Microsoft Excel / Power BI   →  Dashboard & Visual Analytics
🐍 Python (Jupyter Notebook)    →  EDA & Advanced Analysis
🐼 Pandas & NumPy               →  Data Wrangling & Transformation
📉 Matplotlib & Seaborn         →  Statistical Visualizations
🌐 Plotly & Folium              →  Interactive & Map Visualizations
📁 CSV / Open Government Data   →  Raw Dataset Source
```

---

## 📡 Dataset

| Property | Detail |
|---|---|
| **Source** | [data.gov — Electric Vehicle Population Data](https://catalog.data.gov/dataset/electric-vehicle-population-data) |
| **Provider** | Washington State Department of Licensing |
| **Format** | CSV |
| **Records** | 235,690+ registered EVs |
| **Coverage** | US States (WA dominant) |

**Key Columns:**

`VIN` • `County` • `City` • `State` • `Postal Code` • `Model Year` • `Make` • `Model` • `Electric Vehicle Type` • `Electric Range (km)` • `Base MSRP` • `Legislative District` • `DOL Vehicle ID` • `Vehicle Location`

---

## 🔄 Data Pipeline

```
data.gov (CSV)
      │
      ▼
Power Query / Pandas
  ├── Remove duplicate VINs
  ├── Handle missing Electric Range values
  ├── Standardize State & City formats
  ├── Convert Model Year → Integer
  ├── Encode EV Type (BEV / PHEV)
  └── Derive: Range Tier, Adoption Year Group
      │
      ▼
Excel Data Model / Python DataFrame
      │
      ▼
Power BI Interactive Dashboard
```

---

## 📊 Dashboard Modules

### 📈 1. EV Growth by Year
- Sharp adoption curve visible post-**2017**
- Peak registrations observed in **2023** (~60,000+ vehicles)
- Dropdown filter by **Model Year** for granular view

### 🌍 2. Geographic Distribution
- Filled map across US states
- **Washington state** leads significantly in EV registrations
- Urban concentration clearly visible — Seattle, LA, SF corridors

### 🏆 3. Top 10 EV Manufacturers

| Rank | Manufacturer | Registrations |
|---|---|---|
| 🥇 1 | Chevrolet | 17,135 |
| 🥈 2 | BMW | 9,647 |
| 🥉 3 | Chrysler | 3,786 |
| 4 | Audi | 4,360 |
| 5 | Acura | 203 |

### 🔵 4. EV Type Breakdown

```
Battery Electric Vehicle (BEV)     ████████████████████  ~80%
Plug-in Hybrid Electric (PHEV)     █████                 ~20%
```

### 📉 5. Sales & Profit Analysis
- Make-level volume comparison across all manufacturers
- Filters by **State**, **Model Year**, and **Make** for sliced analysis

### ⚡ 6. Electric Range Analysis
- Higher-range vehicles correlate with **post-2020 model years**
- Premium brands (BMW, Audi, Tesla) dominate the 200km+ range tier

---

## 📌 Key Insights

> 💡 **Adoption Surge** — Over 80% of registered EVs are post-2017 models, reflecting the sharp inflection point driven by Tesla's mass-market push and government incentives.
>
> 💡 **Chevrolet Leads Non-Tesla** — With 17,135 registrations, Chevrolet (Bolt EV) is the top non-Tesla EV brand in the dataset.
>
> 💡 **Urban Concentration** — Washington, California, and Florida account for the bulk of EV registrations; rural adoption remains minimal.
>
> 💡 **Range & Recency Correlation** — Vehicles with electric range above 200 km are predominantly 2021+ models from premium manufacturers.
>
> 💡 **BEV vs PHEV Split** — Battery Electric Vehicles dominate (~80%), indicating consumer preference for fully electric over hybrid solutions.

---

## 🧠 Skills Demonstrated

```
✔ Real-world Government Dataset Analysis
✔ Data Cleaning & Wrangling (Power Query + Pandas)
✔ Exploratory Data Analysis (EDA)
✔ Interactive Dashboard Design (Power BI + Excel)
✔ Geographic Visualization (Filled Map + Folium)
✔ Time-Series Trend Analysis
✔ Segmentation & Comparative Analysis (BEV vs PHEV)
✔ Business Storytelling with Data
✔ Python Data Science Pipeline (Pandas, Plotly, Seaborn)
```

---

## 🔮 Future Roadmap

- [ ] 🤖 ML model to predict EV adoption rate by state (time-series forecasting)
- [ ] 🗺️ Folium heatmap for pin-level geographic density
- [ ] ⚡ Charging station overlay — correlate adoption with infrastructure
- [ ] 📱 Streamlit web app for public interactive exploration
- [ ] 🔄 Automated data refresh pipeline via data.gov API
- [ ] 🌍 Expand dataset to include EU and India EV registrations

---

## 📁 Repository Structure

```
📦 EV-Population-Data-Analysis
 ┣ 📊 EV_Dashboard.xlsx              ← Excel analysis & charts
 ┣ 📊 EV_Dashboard.pbix              ← Power BI dashboard
 ┣ 📓 EV_Analysis.ipynb              ← Python EDA notebook
 ┣ 📄 README.md                      ← Project documentation
 ┣ 📁 assets/
 ┃  ┗ 🖼️ ev-dashboard-preview.png   ← Dashboard screenshot
 ┣ 📁 data/
 ┃  ┣ 📋 electric_vehicle_data.csv   ← Raw dataset
 ┃  ┗ 📋 cleaned_ev_data.csv         ← Cleaned dataset
 ┗ 📁 visualizations/
    ┣ 🖼️ growth_trend.png
    ┣ 🖼️ geo_distribution.png
    └── 🖼️ manufacturer_ranking.png
```

---

## 🚀 How to Run

**Excel / Power BI:**
```
1. Download EV_Dashboard.xlsx or EV_Dashboard.pbix
2. Open in Microsoft Excel 2016+ or Power BI Desktop
3. Refresh data connection if prompted
4. Use slicers (State, Model Year, Make) to explore
```

**Python Notebook:**
```bash
# Clone the repository
git clone https://github.com/Anandsavran/EV-Population-Data-Analysis.git
cd EV-Population-Data-Analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn plotly folium jupyter

# Launch notebook
jupyter notebook EV_Analysis.ipynb
```

---

## 📖 References

- [Electric Vehicle Population Dataset — data.gov](https://catalog.data.gov/dataset/electric-vehicle-population-data)
- [Washington State DOL Open Data](https://data.wa.gov/)
- [IEA Global EV Outlook 2024](https://www.iea.org/reports/global-ev-outlook-2024)
- [Microsoft Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)

---

<div align="center">

### 👨‍💻 Author

**Anand Kumar**
B.Tech – Computer Science Engineering (Data Science)
Lovely Professional University, Punjab

<br/>

[![Portfolio](https://img.shields.io/badge/🌐%20Portfolio-anandsavarn.vercel.app-00C896?style=for-the-badge)](https://anandsavarn.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-Anandsavran-181717?style=for-the-badge&logo=github)](https://github.com/Anandsavran)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/)

<br/>

---

*⭐ Star this repo if you found it insightful — it helps others discover it too!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:006600,50:003300,100:0a0a0a&height=100&section=footer" width="100%"/>

</div>
