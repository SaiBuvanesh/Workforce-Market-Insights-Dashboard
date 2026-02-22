# Workforce Market Insights: Global & National Job Intelligence

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-blue?style=for-the-badge)

A data-driven powerhouse that analyzes over **630,000 active job openings** across India and the global Data Science sector. This project transforms raw job postings into a strategic Decision Support System using advanced feature engineering and high-fidelity Power BI reporting.

## 🌟 Project Impact

This isn't just a visualization—it's an economic map. By leveraging custom metrics like **Market Pressure** and **Market Attractiveness**, we've created a tool that helps:
- **HR Leaders**: Identify hiring cyclicality and skill scarcity based on actual market indices.
- **Data Professionals**: Benchmark their worth across global and local markets using engineered salary features.
- **Job Seekers**: Find "High-Opportunity Zones" where demand is high but competition is low.

## 🛠️ The Technical Core

Navigate through the deep-dive documentation:

### 📑 [Deep Data Analysis](./data_analysis.md)
Discover the "Behind the Scenes" logic of the **53 engineered features**. Learn about the encoded categorical markers and the data structure of our custom Market Indices.

### 📊 [Dashboard Visual Guide](./dashboard_guide.md)
A technical manual explaining every graph, card, and slicer. Understand the purpose of the **Opportunity Scatter Plot** and the **Education-ROI Matrix**.

---

## 🖼️ Dashboard Preview

![Dashboard Overview](./Sai%20Buvanesh%20-%20Workforce%20Market%20Insights%20Dashboard.pdf)
> **Direct Access**: [View Full Project Report (PDF)](./Sai%20Buvanesh%20-%20Workforce%20Market%20Insights%20Dashboard.pdf)

> The dashboard tracks 634K openings, ₹8.5 LPA average salary, and 54% role growth.

## 🐍 Data Engineering Logic
While the front-end is powered by Power BI, the backbone of this project involves a Python-based data engineering phase. Python was utilized to:
- **Feature Engineering**: Transform raw postings into sophisticated indices such as *Market Pressure* and *Opportunity Score*.
- **Data Normalization**: Clean and standardize categorical data across multiple source files.
- **Preprocessing**: Encode variables for high-performance dashboard querying and future-ready ML pipelines.

## 📂 Project Structure

```text
├── 1 Indian Job Market/
│   └── 1-Job_Market_India_PowerBI_Final.csv  # 53-col Engineered Dataset
├── 2 Data Science Global Market/
│   └── postings.csv                        # 162K Global Job Records
├── data_analysis.md                        # Technical Data Dictionary & Logic
├── dashboard_guide.md                      # Manual for PBI Visuals
├── Workforce Market Insights Dashboard.pbix # Source Power BI File
└── Sai Buvanesh - Report.pdf               # Presentation Export
```

## 💡 Top Strategic Findings

1. **The Skill Universal**: **Python** and **SQL** aren't just for tech—they are cross-domain essentials for marketing, finance, and engineering in 2026.
2. **Geographical Edge**: While Bangalore and Mumbai are primary hubs, the **City-Salary Adjusted Index** allows for identifying emerging lucrative opportunities where pay is balanced by local economic factors.
3. **PhD Premium**: Higher education level correlates with a higher **Market Attractiveness Score** (1.81 for PhD vs 1.71 avg), particularly in the Data/Tech and Research domains.

---
**Ready to explore?** Open the `.pbix` file to start your interactive journey into the workforce of 2026.

*Created by [Sai Buvanesh](https://github.com/saibuvanesh)*
