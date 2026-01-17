📊 Project Overview

This project is an interactive Power BI dashboard developed to analyze tourist arrivals to Sri Lanka across multiple years.
It provides insights by year, month, country, and continent, enabling users to explore trends, seasonal patterns, and geographic distributions.

The dashboard is designed with a strong focus on data modeling, DAX calculations, and interactive visual storytelling.

🎯 Objectives

Analyze tourist arrival trends over multiple years
Compare monthly and yearly tourist inflow patterns
Visualize geographic distribution of tourists by continent and country
Enable interactive analysis using slicers, decomposition trees, and maps

🗂 Dataset Description

The dataset contains tourist arrival figures categorized by:
Year (2022–2025)
Month
Country of origin
Aggregated totals

A separate dimension table is created for:
Country
Continent (derived using DAX mapping)

🧩 Data Model
The Power BI model follows a star-schema-like structure:
Fact table: Tourist arrival values
Dimension tables:
Country & Continent
Month
Year

Relationships are optimized for filter propagation and performance.

📈 Key Visualizations

The dashboard includes:

🗺 Map Visual
Shows tourist distribution by country
Bubble size changes dynamically based on selected year/month
Legend based on continent

📊 Column Charts
Year-wise and month-wise tourist arrivals
Controlled by Year and Month slicers

🍩 KPI / Donut Visual
Displays actual tourist arrivals vs target

🧠 Decomposition Tree
Enables drill-down analysis by year, month, and continent

🟠 Scatter Plot
Analyzes relationships between monthly and yearly tourist arrivals
Highlights patterns and outliers by continent

🥧 Pie Chart
Displays total tourist arrivals by month
Updates dynamically when a continent is selected

🎛 Interactivity Features
Year slicer to analyze specific years
Month slicer to analyze seasonal patterns
Continent selection using Card (New) visuals
Cross-filtering between visuals (Map, Pie, Column, Scatter)
Dynamic DAX measures responding to slicers and decomposition tree selections

🧮 DAX & Calculations
Key DAX techniques used:
Dynamic measures using SELECTEDVALUE
Conditional logic using SWITCH
Disconnected slicer tables
Calculated columns for continent classification
Measures responsive to visual-level filters

🛠 Tools & Technologies
Power BI Desktop
DAX (Data Analysis Expressions)
Git & GitHub (version control)
Microsoft Excel / CSV (data source)

📌 Key Learnings
Practical implementation of Power BI data modeling
Writing dynamic DAX measures for advanced interactivity
Designing user-friendly and insightful dashboards
Using GitHub to manage and share Power BI projects

🚀 How to Use This Project
Download the .pbix file from this repository
Open it using Power BI Desktop
Use slicers and visuals to explore the data interactively

👤 Author

Yasiru Arachchi
Undergraduate | Data Analytics Enthusiast
Power BI | DAX | Business Intelligence
