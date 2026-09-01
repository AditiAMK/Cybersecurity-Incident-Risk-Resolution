Project Overview

This project analyzes a global cybersecurity threat dataset containing 3,000 cybersecurity incidents from 2015–2024. The objective is to identify patterns in attack frequency, financial impact, affected users, resolution time, vulnerabilities, industries, countries, and defense mechanisms.

The project is designed from a PMO and cybersecurity reporting perspective, with a focus on turning incident data into actionable insights for monitoring, prioritization, and management decision-making.

Objectives
Analyze the frequency of different cyberattack types.
Identify attack types with higher financial and user impact.
Compare cybersecurity incidents across industries and countries.
Analyze security vulnerabilities and defense mechanisms.
Examine incident resolution times.
Build a management-friendly cybersecurity dashboard.
Present data-driven findings and recommendations.
Tools & Technologies
Python — Data preprocessing and cleaning
Pandas — Data handling and analysis preparation
Matplotlib — Data visualization
Microsoft Excel — Exploratory data analysis, PivotTables, and dashboard
Google Colab — Python development environment
Dataset

The dataset contains cybersecurity incident information including:

Country
Year
Attack Type
Target Industry
Financial Loss
Number of Affected Users
Attack Source
Security Vulnerability Type
Defense Mechanism Used
Incident Resolution Time
Data Preprocessing

Python was used to:

Load the raw CSV dataset.
Check missing values.
Check duplicate records.
Verify data types.
Check numerical ranges.
Identify potential outliers using the IQR method.
Standardize unnecessary spaces in text fields.
Export the processed dataset for further analysis.
Exploratory Data Analysis

Excel was used to create PivotTables for:

Attack frequency by attack type
Average financial loss by attack type
Average affected users by attack type
Average resolution time by attack type
Industry-level financial and operational impact
Country-level financial and operational impact
Security vulnerability analysis
Defense mechanism analysis
Key Findings

Some of the major findings from the analysis include:

DDoS had the highest average financial loss among attack types at approximately $52.04 million.
Man-in-the-Middle attacks had the highest average number of affected users at approximately 520,064 users.
Government had the highest average financial loss among target industries at approximately $52.62 million.
Germany had the highest average financial loss among countries at approximately $54.27 million.
Zero-day was the most frequently observed security vulnerability with 785 incidents.
Antivirus showed the highest average financial loss among defense mechanisms at approximately $51.70 million.
VPN had the lowest average resolution time among the analyzed defense mechanisms at approximately 36.86 hours.
Dashboard

The final Excel dashboard presents:

Total number of incidents
Average financial loss
Average affected users
Average resolution time
Attack frequency
Financial impact by attack type
User impact by attack type
Industry-level impact
Vulnerability-related insights
Key management findings
