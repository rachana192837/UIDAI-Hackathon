
📊 Aadhaar Migration Intelligence & Socioeconomic Impact Dashboard

UIDAI – NIC – MeitY Data Hackathon Submission

🔍 Project Overview

This project analyses anonymised Aadhaar enrolment and demographic update data released by UIDAI to uncover internal migration patterns across India and study their socioeconomic implications.

Address-related demographic updates are used as a proxy indicator for migration. The analysis explores how migration trends relate to digital inclusion (mobile number updates), family mobility (child enrolments), regional equity, and seasonal effects.

The project also builds predictive models and an interactive executive dashboard to support data-driven planning and administrative decision-making.

🎯 Objectives

Identify internal migration trends using Aadhaar address update records

Detect regional migration hotspots and seasonal patterns

Analyse relationships between migration, mobile updates, and child enrolments

Quantify socioeconomic impact using regression analysis

Forecast short-term migration trends using ARIMA

Build an interactive decision-support dashboard

📈 Key Visualisations & Dashboards

Interactive dashboards were created using Plotly and exported as standalone HTML files.

🔹 Live Dashboards (via GitHub Pages)

📓 Code & Reproducibility

All data preprocessing, analysis, modeling, and visualisation code is available in the Jupyter notebook:

UIDAI.ipynb

To reproduce the results:

Clone this repository

Install required libraries: 

```bash
pip install pandas numpy matplotlib plotly statsmodels scikit-learn
```
Open and run:
```bash
jupyter notebook UIDAI.ipynb
```
🏆 Hackathon Context

This project was developed as part of the
UIDAI – NIC – MeitY Online Hackathon on Data-Driven Innovation for Aadhaar

The objective is to extract meaningful insights, trends, anomalies, and predictive indicators from Aadhaar enrolment and update data to support informed decision-making and system improvements.
