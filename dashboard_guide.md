# Dashboard Guide: Workforce Market Insights

This guide explains the visual components and technical logic of the Workforce Market Insights Power BI dashboard.

## Key Metrics

The dashboard track three primary indicators:
- **Total Job Openings**: 634,000 active postings in the monitored dataset.
- **Hiring Demand Level**: A composite index (62.9) representing market demand.
- **Average Salary**: ₹8.5 LPA median benchmark.

## Visual Components

### 1. Market Distribution
- **Job Openings by Role**: Treemap showing volume distribution by job title.
- **Job Type**: Charts showing the split between Full-time, Part-time, and Contract roles.

### 2. Opportunity Analysis
- **Demand vs. Competition vs. Salary**: Bubble chart plotting salary level against market pressure and demand. This visual identifies roles with high pay and relatively lower competition.

### 3. Geographic Mapping
- **State-Wise Distribution**: Map highlighting job volume by Indian state.
- **Cost of Living vs. Openings**: Thematic map comparing job density with cost-of-living indices.

### 4. Skill & Education
- **Technical Skills**: Bar chart ranking demand for Python, SQL, and CRM.
- **Education Level**: Analysis of how degree levels (PhD, Masters, Bachelor's) correlate with opportunity access.

## Exploration Features

The dashboard includes several interactive elements:
- **Domain Filter**: Recalculates all visuals for specific sectors like Tech or Healthcare.
- **Experience Slicer**: Adjusts benchmarks for Entry, Mid, and Senior levels.
- **Job Type Slicer**: Toggles between remote, onsite, and hybrid/contract roles.

## Technical Implementation

1. **Modeling**: Star schema design for efficient querying.
2. **Preprocessing**: Data cleaning and feature engineering performed using Python.
3. **Delivery**: Optimized for business stakeholders and job market analysts.
