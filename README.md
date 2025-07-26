# Maternal Health Analysis using DLHS-3 Dataset on IBM Cloud
This repository contains a detailed exploratory data analysis (EDA) of maternal health indicators from the District Level Household and Facility Survey (DLHS-3) dataset obtained from **Open Government Data Platform India**. The goal is to uncover patterns, disparities and relationships in maternal health services across different Indian districts and states.
## Dataset Overview
File: `Maternal_Health-Total_DLHS3.csv`  
Columns include:
- `State_UT`: Name of the State or Union Territory
- `District`: Name of the District
- `First_Trimester_Reg`: % of women registered during the first trimester
- `ANC_3_or_More`: % who received 3 or more Antenatal Care (ANC) visits
- `TT_Injection`: % who received at least one tetanus toxoid injection
- `Institutional_Births`: % of institutional deliveries
- `Home_Delivery_Assisted`: % of home deliveries assisted by health personnel
- `Postnatal_Care_48hrs`: % who received postnatal care within 48 hours
## Objectives
- Analyze trends in maternal health services across districts
- Compare institutional births vs. assisted home deliveries
- Identify top and bottom performing districts for key metrics
- Correlate early registration, ANC, and postnatal care
- Visualize state-wise trends and highlight disparities
## Technologies Used
- Python 3.11
- IBM Cloud Lite services (watsonx.ai studio, cloud object storage, jupyter notebook, python 3.11 env)
- Pandas for data cleaning and manipulation
- Matplotlib & Seaborn for visualizations
- Jupyter Notebook for interactive analysis
## Key Visual Insights
- **Bar plots** comparing top/bottom performing districts
- **Scatter plots** to examine relationships (e.g., early registration vs postnatal care)
- **Histograms** for distribution of institutional births across districts
- **State-wise grouped bar charts** for ANC and delivery metrics
- **Heatmaps** for correlation analysis
