# MTA Ridership Trends and Recovery Analysis - Support Future Modeling of Congestion Pricing Impacts

This project analyzes the ridership trends of different modes of public transportation operated by the **Metropolitan Transportation Authority (MTA)** in New York City between **2020 and 2025**, focusing on the pandemic's impact and post-pandemic recovery.

## Project Goal

To perform Exploratory Data Analysis (EDA) and visualize trends in **daily ridership** across various MTA transit modes (Subway, Bus, LIRR, Metro-North, and Staten Island Railway), identifying:
- How the COVID-19 pandemic affected transit usage
- Differences in recovery patterns across transit modes
- Implications for **Congestion Pricing Policy** and transit planning

---

## Dataset

- **Source:** MTA Weekly Transportation Usage Reports
- **Period:** 2020 to early 2025
- **Columns:**
  - `subways_total_estimated_ridership`
  - `buses_total_estimated_ridersip`
  - `lirr_total_estimated_ridership`
  - `metro_north_total_estimated_ridership`
  - `staten_island_railway_total_estimated_ridership`
  - (and their comparisons to pre-pandemic levels)

---

## Key Analyses

### Data Preprocessing
- Checked for missing values and corrected column inconsistencies
- Converted date formats and handled time-based indexing

### Individual Mode Trend Visualization
Each mode is visualized separately to avoid clutter and better understand the trends:
- **Subway Ridership:** Steady recovery but still below pre-pandemic highs
- **Bus Ridership:** Quickest rebound and most stable recovery
- **LIRR & Metro-North:** Slower growth reflecting changes in commuter behavior
- **Staten Island Railway:** Least utilized, slowest to recover

### Comparative Summary
A consolidated conclusion evaluates recovery percentages and volatility across all systems, identifying modal shifts and supporting congestion pricing discussions.

---

## Technologies Used

- **Python 3.13.2
- **Pandas** for data manipulation
- **Matplotlib** & **Seaborn** for visualization
- **Jupyter Notebook** for documentation

---

## Project Conclusion: Summary Insights

- **All modes suffered a sharp drop in 2020** due to the pandemic.
- **Bus ridership recovered the fastest**, reaching ~90% by 2025.
- **Subways hovered around 85%**, while **commuter rails (LIRR, Metro-North)** showed ~70–75% recovery.
- **Staten Island Railway** remained at ~50–60%.
- The analysis supports **policy planning for congestion pricing**, future investments, and MTA service reallocation.

---

## Relevance to Congestion Pricing

These findings provide critical data to evaluate:
- Travel behavior changes post-COVID
- Transit corridor recovery
- Policy design for pricing, equity, and investment

---

## Repository Structure

├── mta_dataanalysis.ipynb # Jupyter notebook with full EDA & visualization
├── README.md # This file


## Acknowledgments

- Data sourced from the [MTA Open Data Portal](https://data.ny.gov/) and official MTA Transportation Reports.
- Inspired by current policy initiatives such as congestion pricing and post-pandemic urban mobility trends in NYC.

---

## Contact

**Author:** Tasnia Sultana  
**Email:** [sultanatasniaeee92@gmail.com]  

Feel free to reach out for collaboration, questions, or feedback!





