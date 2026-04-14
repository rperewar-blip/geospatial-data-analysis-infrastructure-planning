# Geospatial Data Analysis for Infrastructure Planning

## Project Overview
This project analyzes NYC collision data to identify crash patterns, contributing factors, vehicle involvement, severity distribution, and geospatial hotspots. The objective is to support infrastructure planning and traffic safety improvement through data-driven insights.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Folium
- Jupyter Notebook

## Dataset
The dataset contains NYC collision records, including:
- crash date and time
- latitude and longitude
- borough
- injury and fatality counts
- contributing factors
- vehicle type information

## Project Workflow
1. Loaded and cleaned the collision dataset
2. Standardized column names
3. Handled missing values and removed invalid coordinates
4. Performed feature engineering for time and severity analysis
5. Conducted exploratory data analysis on borough trends, monthly crash patterns, contributing factors, and vehicle types
6. Built an interactive geospatial map using Folium
7. Generated infrastructure planning insights based on crash concentration and severity

## Key Insights
- Brooklyn and Queens showed the highest crash counts and total casualties
- Crash frequency varied across months, indicating time-based trends
- Driver inattention/distraction was the leading contributing factor after excluding unspecified entries
- Sedans and SUVs were the most commonly involved vehicle types
- The interactive map highlighted dense crash hotspots in major urban areas

## Business Impact
The findings can support:
- road safety improvements
- traffic signal optimization
- targeted enforcement strategies
- resource allocation for infrastructure planning
- urban traffic risk assessment

## Files in This Repository
- `notebooks/Geospatial_Data_Analysis_Infrastructure_Planning.ipynb` — full project notebook
- `data/crashes_cleaned_final.csv` — cleaned dataset
- `outputs/crash_map.html` — interactive geospatial map
- `images/` — saved visualizations
- `README.md` — project documentation

## Conclusion
This project demonstrates how geospatial and operational traffic data can be analyzed to identify high-risk zones and support data-driven infrastructure and safety planning.
