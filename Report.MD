# Introduction
The 2021 Marketing Performance Dashboard project was developed to provide a complete end-to-end analysis of digital marketing campaigns.
Using Excel’s Power Query, Power Pivot, and Pivot Tables, the dashboard transformed raw data into actionable insights. The focus was on five core KPIs; Total Impressions, Total Clicks, Average Acquisition Cost, 
Average Conversion Rate, and Total ROI, while also tracking trends, weekly breakdowns, channel and campaign performance, ROI by location, and audience targeting.

# Data Preparation
Imported datasets of about **17** columns and **200000** Rows from Excel as a CSV File.
![My Image Description](https://github.com/R887645/2021-Marketing-Performance-Dashboard-Report/blob/main/Data%20Preparation.png?raw=true)

# Data Cleaning in Power Query

- Removed nulls and duplicates.

- Normalized text and corrected data types (numbers, currency, percentages, dates).

- Ensured acquisition cost values were consistent and rounded.

# Date Table Creation
- Split a dynamic Date Table covering the full year.

- Added columns for Year, Month, Month Name, Week, and Quarter for PM and MoM comparisons.

- Enabled time intelligence functions for weekly and monthly trend analysis.

# Data Modeling in Power Pivot
- Designed a one-to-many relationship linking the marketing table to the Date table only.

- Established filter directions to ensure timeline slicers worked correctly.

- Allowed flexible analysis across KPIs, weekly trends, and segmented breakdowns.

![My Image Description](https://github.com/R887645/2021-Marketing-Performance-Dashboard-Report/blob/main/Power%20Pivot(Data%20Modelling).png?raw=true)

# DAX Measures in Power Pivot & Pivot Tables
- Defined measures for:

  - **Total Impressions:** 1101.46M

  - **Total Clicks:** 109.95M

  - **Average Acquisition Cost:** $12.50K

  - **Average Conversion Rate:** 8.0%

  - **Total ROI:** $1.00M

- Created comparative measures:

  - **MOM% Change:** Impressions +9.29%, Clicks +9.32%, ROI +109.27%

  - **PM:** Impressions 1007.6M, Clicks 100.66M, Conversion Rate 8.0%, ROI $915.6K, Acquisition Cost $12.50K

![My Image Description](https://github.com/R887645/2021-Marketing-Performance-Dashboard-Report/blob/main/All%20DAX%20measures%20.png?raw=true)

# KPI Results and Trends

- Strong growth in impressions and clicks compared to PM.

- ROI more than doubled, showing improved efficiency.

- Acquisition cost remained stable across weeks.

- Conversion rate held steady at 8.0%, with a slight uptick in Week 6.

![My Image Description](https://github.com/R887645/2021-Marketing-Performance-Dashboard-Report/blob/main/Real%20End%20to%20End%20Marketing%20Performance%20Dashboard.png?raw=true)

# Weekly Trends
- Impressions peaked in Weeks 2–4 (~253M each).

- Clicks followed a similar pattern, peaking in Weeks 2–4 (~25M each).

- Week 6 showed a sharp decline (Impressions 12.05M, Clicks 1.22M).

- Acquisition Cost remained stable ($12.48K–$12.61K).

- Conversion Rate consistent at 8.0%, rising to 8.1% in Week 6.

# Channel Performance
- **By Impressions**: Google Ads (185.01M), Email (184.80M), Website (183.81M).

- **By ROI:** Email ($167.88K), Google Ads ($167.30K), Website ($167.27K).

- Email slightly outperformed in ROI despite similar impression volumes.

# Campaign Type Performance
- **By Impressions:** Search (221.42M), Influencer (220.77M), Email (220.14M).

- **By ROI:** Influencer ($201.29K), Search ($201.12K), Display ($200.20K).

- Influencer campaigns delivered the highest ROI, validating their strategic value.

# ROI by Location
- **Miami:** $201.84K

- **Los Angeles:** $200.17K

- **Chicago:** $200.11K

- **New York:** $199.33K

- **Houston:** $199.04K

- Miami led in ROI, suggesting stronger campaign resonance.

# Target Audience by Impression
- **Men 18–24:** 221.23M

- **Women 25–34:** 220.45M

- **Men 25–34:** 220.39M

- **Women 35–44:** 219.04M

- **All Ages:** 221.42M

- Young male audiences **(18–24)** were the most targeted, aligning with campaign goals.

# Recommendations
- **Geographic Focus:** Allocate more budget to Miami; optimize campaigns in New York and Houston.

- **Campaign Strategy:** Expand influencer marketing; maintain strong investment in search.

- **Channel Optimization:** Refine email strategy to leverage its ROI advantage.

- **Audience Targeting:** Continue focus on Men 18–24; diversify messaging for Women 25–34.

- **Trend Monitoring:** Investigate Week 6 drop in impressions and clicks to avoid campaign fatigue.

- **Conversion Improvement:** Optimize creatives and landing pages to push conversion rate above 8.0%.

# Conclusion
The 2021 Marketing Performance Dashboard demonstrates how clean data, structured modeling, and DAX-driven measures can transform raw campaign information into actionable insights. The analysis highlights strong growth in impressions and clicks, stable acquisition costs, and a significant ROI increase.
With targeted geographic adjustments, expanded influencer strategies, and refined email campaigns, future efforts can achieve even greater efficiency and impact.

Beyond showcasing technical execution, this project reflects my ability to take complex datasets and translate them into clear, strategic recommendations. 
If you are looking to build dashboards, optimize KPIs, or analyze marketing performance data, I am available to help you analyze your campaigns and guide you toward data-driven decisions.
