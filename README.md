# Flooding Incident Analysis

## Overview
Processes unstructured flooding incident reports collected from the Iowa State University National Weather Service Archive and emergency coordinators.  
Normalizes text data, extracts important fields (such as street names and event types), and visualizes flooding patterns that could help emergency planners.

## Data
- **Source**: Iowa State University NWS Archive and emergency coordinator incident logs
- **Format**: Unstructured incident reports (text)  
- **Challenges**: Inconsistent capitalization and street suffix inclusion in flood reports 

## Methods
- Extraction of key features (street names, location, event type)  
- Regex-based normalization for text cleaning  
- Pivot tables and charts for analysis  
- Visualizations to highlight flood-prone areas  

## Tools
- Python (Pandas, Regex, Dictionary)  
- Excel (Pivot Tables, Charts)   

## Results
- Structured raw reports into a clean dataset  
- Visualizations of flooding hotspots across St. Charles Parish  
- Presented findings to Homeland Security & Emergency Preparedness officials  

# Example Visualization
Using Excel pivot tables, I created a pie chart summarizing the number of flood reports for streets nearby local schools. The chart revealed that five streets accounted for more than 55% of total reports. This insight suggested that emergency coordinators should prioritize mitigation strategies in these areas.

([2025_Summer_Analysis\Charts\Reports_Near_Target_Schools.png](https://github.com/cordialApple/flood-report-analysis/tree/main/Summer%202025%20Analysis/Charts/Reports_Near_Target_Schools.png))

## Impact
- Reduced manual processing time for analyzing raw reports  
- Provided data-driven insights to prioritize infrastructure needs  

## Repository Contents
- `Charts/` –  Collection of charts derived from pivot tables and presented to Director and Senior Emergency Coordinators
- `Luling_Demo.csv/` – Sample dataset extracted from raw data by filtering for Luling flood reports
- `Project_Overview.ipynb` – Jupyter notebooks with data cleaning + analysis steps 


👉 More charts available in ([2025_Summer_Analysis\Charts](https://github.com/cordialApple/flood-report-analysis/tree/main/Summer%202025%20Analysis/Charts)).





