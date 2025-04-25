# DSA210-Data-Science-Project
Comparison of the Sum of Total Number of Passengers by Year and Metro Line  Which Managed by Istanbul Metro
Project Proposal
1. Project Motivation
Public transportation is essential for urban mobility, and the Istanbul Metro, managed by Metro Istanbul, plays a critical role in reducing congestion and providing efficient travel. This project aims to analyze and compare the total number of passengers by year and metro line to understand trends in metro usage. The key research questions include:
•	How has metro ridership evolved over the years?
•	Which metro lines have experienced the highest passenger growth?
•	How do newly opened metro lines impact ridership distribution?
The findings from this study could provide insights for urban planners and policymakers to improve metro services and predict future transportation needs.

2. Data Sources
The primary dataset for this project will be obtained from Metro Istanbul’s official passenger statistics page:
https://www.metro.istanbul/yolcuhizmetleri/yolcuistatistikleri 
This source provides annual passenger numbers for each metro line, which will be used to track changes over time.

Additional supporting datasets may be sourced from:
•	İstanbul Büyükşehir Belediyesi (İBB) Open Data Portal
https://data.ibb.gov.tr (if relevant transportation or demographic data is found)
•	TÜİK (Turkish Statistical Institute)
https://data.tuik.gov.tr (for population growth trends, which could be used for correlation analysis)

3. Data Collection Plan
The data collection process will follow these steps:
1.	Extract ridership data: Download annual metro ridership statistics from the Metro Istanbul website.
2.	Organize the data: Structure the dataset in a tabular format (CSV or JSON), including metro line names and annual passenger counts.
3.	Cross-check and enrich the data: If additional datasets (such as new metro openings or population growth statistics) are available, they will be incorporated.
4.	Prepare for analysis: Perform initial data cleaning and preprocessing to ensure consistency and completeness.
 
Kemal Arda Adışen 30820 

## Phase 2 – Data Analysis & Hypothesis Testing

In Phase 2, the dataset was extended from yearly totals to monthly ridership values (2019–2024), including all metro, tram, funicular, and cable car lines managed by Metro Istanbul.

### ✅ Key Additions:
- Structured monthly-level dataset
- Visualizations of ridership trends over time
- Line-by-line bar charts
- T-tests to compare average monthly ridership across years

### 📁 Files Added:
- `data/istanbul_metro_monthly_all_lines_with_tram_funicular.csv` – Cleaned and enriched dataset
- `notebooks/metro_analysis.ipynb` – All EDA, plots, and hypothesis testing
- `requirements.txt` – Python package dependencies

### 🧪 Example Result:
Using a two-sample t-test, we found that the average monthly ridership of the M2 line did **not** change significantly from 2019 to 2024 (p = 0.6696).

Other lines, such as M7 or T5, showed more variation and were also tested.
