# United-States-Emissions-Breakdown-Databricks-Analytics-Project
This project analyzes U.S. county-level greenhouse gas emissions using data sourced from the EPA (2023).
I built an interactive analytics dashboard in Databricks SQL, with each visual powered by its own SQL query.
The goal was to explore geographic emission patterns, compare states and counties, and understand how population relates to emissions.

 Project Overview

The dataset contains:

County & state identifiers

Population values

Total GHG emissions (metric tons of CO₂e)

Latitude / longitude coordinates

Using Databricks SQL, I cleaned, transformed, and visualized the data to uncover trends and regional differences.

 Dashboard Insights

Key findings from the dashboard:

Counties with larger populations generally show lower emissions per person

Maricopa County (AZ) and Harris County (TX) rank among the highest total emitters

Several southern and industrial Midwest states contribute disproportionately to total emissions

Geographic mapping reveals clear clusters of high-emission counties across the U.S.

The dashboard includes:

Map of emissions across continental U.S.

Scatter plot: emissions per person vs population

Top 10 counties by total emissions

Top 10 states by total emissions

Donut chart for state-level breakdown

🛠️ Tools & Techniques

Databricks SQL (dashboard builder + SQL analytics)

Data cleaning with try_cast, replace, and nullif

Ranking and aggregation with SQL

Geospatial visualization using latitude & longitude

Trend analysis using scatter charts

Dataset quality handling (malformed numeric values)
