# COVID-Analytics


## Description
A comprehensive multi-layered analysis system for COVID-19 data that integrates data collection, validation, statistical reasoning, and governance reporting. This project provides actionable insights into pandemic impacts across different regions through interactive visualizations and policy simulation tools.

## Project Structure
├── Barnabus/
│ ├── cleaned_covid_data.csv
│ ├── Combinedatagoogle&worldbank.csv
│ ├── Layer1_Data_Collection.py
│ ├── Layer2_Validation.py
│ ├── Layer3_Statistical_Reasoning.py
│ ├── Layer4_Governance.py
│ ├── Dashboard.py
│ ├── html_output/
│ │ └── dashboard.html
│ ├── output/
│ │ ├── charts/
│ │ ├── tables/
│ │ ├── governance/
│ │ │ ├── logs/
│ │ │ └── reports/
│ │ └── all result/
│ └── requirements.txt
├── README.md


## Quick Start
1. **Project Setup**:
   - Place all project files in the `Barnabus` folder on your desktop
   - Ensure `cleaned_covid_data.csv` is in the root of the Barnabus folder

2. **Install Dependencies**:
 pip install -r requirements.txt

3.**Run Analysis Pipeline:
Full Pipeline (Run sequentially):
python Barnabus/Layer1_Data_Collection.py
python Barnabus/Layer2_Validation.py
python Barnabus/Layer3_Statistical_Reasoning.py
python Barnabus/Layer4_Governance.py
python Barnabus/Dashboard.py


Accelerated Execution (if cleaned_covid_data.csv exists):
python Barnabus/Layer2_Validation.py
python Barnubar/Layer3_Statistical_Reasoning.py
python Barnabus/Layer4_Governance.py
python Barnabus/Dashboard.py

4.**View Results:
Open Barnabus/html_output/dashboard.html in your browser
Additional outputs available in Barnabus/output/ folder

Analysis Layers
Layer 1: Data Collection & Preprocessing
Sources: World Bank, Google COVID-19 Open Data, OWID
Features:
Automated data integration from multiple sources
Missing value handling and data cleaning
Weekly/annual aggregation
Feature engineering for health indicators
Output: Preprocessed datasets with unified structure
Layer 2: Validation & Anomaly Detection
Methods:
Missing value analysis
IQR and Z-score outlier detection
Temporal irregularity detection
Explainable logging
Output: Validation reports with actionable insights
Layer 3: Statistical Reasoning
Analyses:
Time series smoothing (MA, EWMA, ARIMA)
Correlation analysis
Regression modeling with multicollinearity handling
Regional equity comparisons
Vaccine impact assessment
Output: Statistical models and insights
Layer 4: Governance & Reporting
Features:
Structured JSON/CSV logging
Automated summary reports
Version control integration
Audit trails
Output: Governance reports and audit logs
Dashboard Features
Multi-layer Navigation: Tabbed interface for each analysis layer
Interactive Visualizations:
Regional comparison charts
Time series analysis
Correlation matrices
Anomaly detection visualizations
Drill-down Capabilities: Filter by WHO region and time period
Policy Simulation Tool: Simulate indicator improvements and impacts
Responsive Design: Works on desktop and mobile devices




Dependencies
pandas==1.5.3
numpy==1.24.3
matplotlib==3.7.1
seaborn==0.12.2
scikit-learn==1.3.0
scipy==1.11.1
statsmodels==0.14.0
plotly==5.15.0
flask==2.3.2
requests==2.31.0
beautifulsoup4==4.12.2
pillow==10.0.0
gitpython==3.1.31



# Data Sources
Data_Collection
🌍 COVID-19 Analytics: Multi-source (World Bank + Google + github) time series, regression &amp; interactive dashboard
World Bank Indicators: Socio-economic and health system data (URL: https://databank.worldbank.org/home)
Google COVID-19 Open Data: Daily COVID-19 statistics (URL: https://health.google.com/covid-19/open-data/raw-data)
Our World in Data (OWID): Comprehensive COVID-19 dataset (URL: https://raw.githubusercontent.com/owid/covid-19-data/refs/heads/master/public/data/owid-covid-data.csv)


# Sample Insights
Regional Disparities: Identified significant differences in death rates between WHO regions
Vaccine Impact: Quantified 10% vaccination rate improvement leads to 7% reduction in death rates
Anomaly Detection: Flagged 237 data anomalies requiring investigation
Health System Correlation: Strong correlation (r=0.78) between hospital bed availability and mortality rates



# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Contributing
Fork the repository
Create a feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

# Contact
Mahnaz Nouri

GitHub: Mahnaznoori
Email: mahnaznoori@gmail.com ;
      Mahnaznouri1981@gmail.com
      
# Project Link:
https://github.com/Mahnaznoori/COVID-Analytics

# Acknowledgments
World Bank for socio-economic indicators
Google Health for COVID-19 open data
Our World in Data for comprehensive datasets





   




