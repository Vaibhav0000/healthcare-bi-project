# healthcare-bi-project
# Healthcare Drug Use Analytics Platform

## 🔍 Project Overview

A data-driven investigation into drug use patterns across U.S. healthcare settings (ED, IP, OP) to uncover key demographic, geographic, and socioeconomic insights. Built to support data-backed interventions and resource allocation.

## 🧠 Real-World Scenario

This project simulates a real-world public health research initiative. We sourced healthcare facility-level drug use data and paired it with U.S. census-based socioeconomic data to analyze:

* Who is affected most by drug use?
* Where are the hotspots?
* What social and economic factors correlate with these trends?

## 📂 Repository Structure

```
healthcare-drug-use-analytics/
├── README.md
├── data/
│   ├── aggregated_by_hospital.csv
│   ├── aggregated_by_state.csv
│   ├── figure_all_drugs_by_demographics.csv
│   ├── figure_all_drugs_by_urban_rural.csv
│   ├── figure_benzodiazepines_by_demographics.csv
│   ├── figure_cannabis_by_demographics.csv
│   ├── figure_opioids_by_demographics.csv
│   ├── figure_stimulants_by_demographics.csv
│   ├── figure_summary_all_settings.csv
│   ├── full_analysis_data.csv
│   ├── healthcare_data.csv
│   ├── socioeconomic_data.csv
│   ├── Hospital_General_Information.csv
│   └── state_socioeconomic_yearly.csv
├── notebooks/
│   └── drug_use_analysis_colab.ipynb
├── dashboards/
│   └── dashboard_images/
│       ├── dashboard 1.png
│       ├── dashboard 2.png
│       ├── dashboard 3.png
│       └── dashboard 4.png
├── documentation/
│   ├── Summary Final.pdf
│   └── Detailed Report Final.pdf
│   └── Glossary.pdf
│   └── PM.pdf
└── LICENSE
```

## 🛠️ Tools Used

* **Google Colab**: Data wrangling, transformation, validation
* **Python**: Pandas, NumPy, Matplotlib
* **Tableau**: Interactive dashboards and storyboards
* **Excel**: Initial data review

## 📊 Key Dashboards & Insights

* **Overview Dashboard**: Drug-related visits per setting across the U.S.
* **Demographic Analysis**: Opioid and cannabis usage disproportionately affecting youth and rural populations
* **Geographic Trends**: West Virginia & New Mexico as top states per capita; socioeconomic correlation evident
* **Facility-Level Patterns**: A handful of facilities account for a large share of drug-related visits

## 📈 Validated Insights

1. **Over 60%** of all drug-related incidents occurred in Emergency Departments.
2. **Opioids and Cannabis** were the top reported drugs.
3. **Rural counties and youth** showed higher per capita drug-related visits.
4. **West Virginia and New Mexico** had the highest per capita cases, linked to low median income.

## 📥 Data Sources

* **Healthcare Dataset**: [U.S. Department of Health and Human Services Open Data Portal](https://healthdata.gov)
* **Socioeconomic Dataset**: [U.S. Census Bureau - ACS 5-Year Data](https://data.census.gov)

## ▶️ Demo

*Available in [Final Video Walk Through](https://drive.google.com/file/d/14JWPkNZdPiaVKG-on70i7fiIJevOviJa/view?usp=drive_link)*

## 📩 Contact

Vaibhav Nangia
**Business Data Analyst | PMP-Certified Project Manager | BI Storyteller**
[LinkedIn](https://www.linkedin.com/in/vaibhavnangia08050805/) | [Email](mailto:your.nangiavaibhav9@gmail.com)
