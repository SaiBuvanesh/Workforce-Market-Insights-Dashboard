# Workforce Market Insights Dashboard

A data-driven analysis of 630K+ job openings in India and 160K+ global Data Science roles. This project uses Power BI to visualize market trends, salary benchmarks, and demand intensity across various job domains.

## 📊 Documentation
Detailed technical information is available in the following guides:
- [Data Analysis](./data_analysis.md): Engineered features and feature engineering logic.
- [Dashboard Guide](./dashboard_guide.md): Technical breakdown of Power BI visuals and slicers.

## 🖼️ Project Report
![Dashboard Overview](./Sai%20Buvanesh%20-%20Workforce%20Market%20Insights%20Dashboard.pdf)
> [View Full Project Report (PDF)](./Sai%20Buvanesh%20-%20Workforce%20Market%20Insights%20Dashboard.pdf)

## 🛠️ Implementation Details
- **Data Engineering**: Python was used to clean raw datasets and create custom metrics like `market_pressure` and `opportunity_score`.
- **Visualization**: Power BI Desktop was used for interactive reporting and spatial mapping.
- **Datasets**: 
  - `1 Indian Job Market`: 30,000+ records with 53 engineered features.
  - `2 Data Science Global Market`: 162,000+ scraped global job postings.

## 📂 Repository Structure
```text
├── 1 Indian Job Market/
│   └── 1-Job_Market_India_PowerBI_Final.csv
├── 2 Data Science Global Market/
│   └── postings.csv
├── data_analysis.md
├── dashboard_guide.md
├── Workforce Market Insights Dashboard.pbix
└── Sai Buvanesh - Workforce Market Insights Dashboard.pdf
```

## 💡 Key Insights
- **Skill Demand**: Identifying cross-role demand for Python and SQL in non-tech sectors.
- **Geographic Value**: Using city-salary adjusted indices to find high-value regions.
- **Education ROI**: Correlating degree levels with market attractiveness scores.

---
[Sai Buvanesh](https://github.com/saibuvanesh)*
