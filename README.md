# Smart Energy Analytics – Home Energy Optimization Dashboard

## Project Overview
This project delivers an interactive Excel-based analytics dashboard for smart building energy management focusing on energy efficiency, HVAC performance, tenant comfort, and maintenance reliability using sensor and maintenance log data.
The solution demonstrates data transformation, KPI automation, and dashboard design aligned with real-world energy management challenges.

## Project Objectives
-	Identify energy inefficiencies and peak demand patterns
-	Analyze HVAC behavior under varying environmental conditions
-	Evaluate tenant comfort compliance
-	Detect maintenance risk and failure concentration
-	Support data-driven operational decisions
  
## Data Sources
-	Sensor Data: Temperature, humidity, HVAC settings, energy consumption, occupancy
-	Maintenance Logs: Unit ID, issue type, resolution method, timestamps
  
## Data Preparation
-	Cleaned and structured datasets using Excel tables
-	Detected and removed energy outliers using Z-score (|Z| > 3)
-	Filled missing values using unit-level averages
-	Engineered features:
o	Time (month, day, season, time-of-day)
o	Comfort ranges (ASHRAE-based)
o	HVAC workload classes
o	Energy cost ($0.15/kWh)
o	Failure intervals & MTBF

## Key KPIs
-	Total Energy Consumption (kWh)
-	Energy Cost per Unit ($)
-	Energy Waste Percentage
-	Tenant Comfort Score (%)
-	Temperature Comfort Compliance (%)
-	HVAC High-Intensity Operation (%)
-	Total Maintenance Failures
-	Mean Time Between Failures (MTBF)
  
## Key Insights
-	Energy consumption is highly seasonal, driven by HVAC demand
-	Nearly 50% of HVAC operations run at high intensity
-	Only 12% of conditions meet comfort standards
-	Energy usage is concentrated among a small subset of tenants
-	Maintenance issues are unit-specific rather than system-wide
  
## Dashboard Features
-	Interactive KPI cards
-	Slicers (Unit, Month, HVAC Class, Time Period)
-	Energy, comfort, and maintenance visuals
-	Export-ready dashboard (PNG)
  
## Tools
-	Microsoft Excel

## Live Dashboard
The interactive Excel dashboard is hosted on OneDrive for easy viewing:
[Open Live Excel Dashboard](https://atara788-my.sharepoint.com/:x:/g/personal/omololabankole_atara788_onmicrosoft_com/IQDwNIvKXh4LSqluokY47GGPAd9AV6ehzHolwz-_qs4Ht3E?e=dEbUpM)


