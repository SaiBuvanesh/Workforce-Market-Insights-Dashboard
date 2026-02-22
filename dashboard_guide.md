# Dashboard Guide: Workforce Market Insights

This guide explains the visual architecture of the Power BI dashboard, detailing the technical purpose and user logic behind each element.

## 🏆 Key Performance Indicators (KPIs)

At first glance, three core "Big Number" cards establish the market's scale:
- **Total Job Openings (634K)**: The absolute volume of monitored active postings.
- **Hiring Demand Level (62.9)**: A composite measure of market heat.
- **Average Salary (₹8.5 LPA)**: The median benchmark for professional roles in India.

## 🧩 Visual Component Analysis

### 1. Market Distribution (Treemaps & Donuts)
- **Job Openings by Role**: A nested treemap showcasing that Marketing and Teaching lead in volume, while Data Science maintains high priority despite lower raw counts.
- **Job Type Splits**: A donut chart illustrating the balance between Full-time (largest), Part-time, and Contract work.

### 2. Opportunity Intelligence (Scatter Plots)
- **Demand vs. Competition vs. Salary**: This visual uses bubble size to represent salary, X-axis for competition (Pressure), and Y-axis for Demand.
- **Strategic Insight**: Areas with large bubbles (high salary) on the left side (low pressure) represent **High Opportunity Zones**.

### 3. Geographic & Economic Maps
- **State-Wise Landscape**: Map visualization highlighting Karnataka and Maharashtra as primary hubs.
- **Cost of Living vs. Openings**: A thematic map identifying states where high job density overlaps with favorable cost-of-living indices.

### 4. Skill & Education Matrix
- **Core Skills Bar Chart**: Ranks Python, SQL, and CRM as the "Universal Skills" making candidates more resilient across domains.
- **Education Level ROI**: A line-area chart showing the direct correlation between advanced degrees (PhD/Masters) and opportunity access.

---

## ⚙️ Interactive Controls (Slicers)

The dashboard is designed for deep-drill exploration using:
- **Domain Filter**: Toggle between Tech/Healthcare/Engineering to see a completely recalibrated market view.
- **Experience Level**: Adjust from Entry to Senior to see how salary benchmarks shift.
- **Job Type**: Filter by Contract vs. Full-time to spot remote-friendly sectors.

---

## 🎬 Technical Flow

1. **Sourcing**: Python-preprocessed CSV files.
2. **Modeling**: Star schema design within Power BI for optimal query performance.
3. **Visual Selection**: Data-to-ink ratio optimization to ensure clarity even with high data density.
4. **Insight Delivery**: Designed for HR Managers to identify hiring trends and Professionals to benchmark their worth.

---
> [!NOTE]
> This dashboard isn't just a report; it's a **Decision Support System**.
