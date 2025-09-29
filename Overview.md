🌍 Ozone Pollution Analysis in California
📌 Overview

This project analyzes ozone pollution levels across California using daily monitoring data from the U.S. Environmental Protection Agency (EPA).
The dataset contained missing values, inconsistent formats, and outliers, so an extensive data cleaning and validation process was performed before analysis.

The final report categorizes California regions into four risk zones based on average ozone concentration (mean) and its variability (standard deviation):

✅ Good = Low Mean, Low Std

📡 Unstable = Low Mean, High Std

⚠️ Dangerous = High Mean, Low Std (consistent chronic risk)

🚨 Bad = High Mean, High Std

🧪 Methodology

Data Cleaning

Handled missing values, duplicates, and inconsistent date formats.

Standardized measurement units (ppm).

Validated outliers using z-scores and contextual thresholds.

Exploratory Data Analysis (EDA)

Trends of daily maximum 8-hour ozone concentration over time.

Regional comparisons to identify consistently high-pollution areas.

Analysis of differences across measurement methods.

Urban activity patterns: weekday vs. weekend ozone levels.

Geospatial heatmap visualization of high ozone concentration zones.

Zonal Risk Classification

Categorized regions into Good, Unstable, Dangerous, and Bad.

Highlighted how consistent high ozone levels (high mean, low std) are more harmful than occasional spikes due to chronic health impacts.

📊 Key Insights

🚨 Consistently High-Risk Zones: Regions like Yuba City and Chico show persistently high ozone with low variability — indicating chronic pollution.

⚠️ Dangerous Fluctuating Zones: Areas such as Fresno and Riverside have high means with high variability — requiring adaptive monitoring and seasonal interventions.

📡 Unstable Zones: Sacramento and Stockton regions show sudden spikes despite lower averages — requiring real-time monitoring.

✅ Good Zones: Regions like San Francisco and Santa Cruz maintain low and stable ozone levels — these should be preserved as policy benchmarks.

🎯 Recommendations

Critical Response in “Bad Zones” → Long-term emission control, urban greening, stricter traffic/industrial regulation.

Targeted Oversight in “Dangerous Zones” → Seasonal interventions, adaptive alert systems.

Real-Time Monitoring in “Unstable Zones” → Predictive sensors and dynamic public alerts.

Preserve Good Zones → Continue preventive measures, promote sustainable transit and clean energy.

Standardize Monitoring Methods → Method 199 consistently reports higher readings; calibration audits recommended.

📌 Visualizations

The interactive report was built in Power BI and includes:

Time-series trends of ozone levels.

Regional scatter plots with risk-zone classification.

Stacked column comparisons of monitoring methods.

Weekday vs. weekend ozone analysis.

Geospatial heatmap of high-ozone regions.
