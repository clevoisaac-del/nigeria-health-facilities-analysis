# Nigeria Health Facilities Analysis

End-to-end exploratory data analysis of health facilities across Nigeria.

## Project Overview
This project analyzes a large dataset of health facilities in Nigeria to understand their distribution, types, functional status, and geographic coverage. The goal is to generate actionable insights for healthcare planning and policy.

## Key Findings
- The health system is heavily dominated by *Primary* facilities (over 43,900)
- *Secondary* facilities: 1,338 | *Tertiary* facilities: 800
- Majority of facilities are *Functional* (34,282), but a large number have *Unknown* status (11,753)
- Facility distribution across states is uneven
- Data quality issues exist, especially in functional status reporting

## What I Did
- Data loading and cleaning
- Exploratory Data Analysis (EDA)
- Analysis of facility types, functional status, and categories
- Geographic distribution analysis by state
- Created visualizations (count plots, bar charts, grouped analysis)
- Generated insights and policy recommendations
- Designed an Executive Summary presentation

## Tech Stack
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

## How to Run
```bash
pip install -r requirements.txt

## Dataset
Nigeria Health Facilities dataset (sourced from Humanitarian Data Exchange - HDX)

## Project Structure
```
nigeria-health-facilities-analysis/
├── Nigerian_Health_Facilities_Analysis.ipynb
├── Nigeria_Health_Facilities_Executive_Summary.pptx
├── requirements.txt
└── README.md
```

## Key Insights
- Nigeria has a strong primary healthcare base but limited secondary and tertiary capacity
- High number of facilities with "Unknown" functional status reduces data reliability
- Uneven distribution of facilities across states creates access inequality
- Strengthening primary healthcare functionality and data systems should be prioritized
