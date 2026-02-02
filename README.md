# Due to the large size of the dataset, the file was stored locally and processed using chunk-based loading to avoid memory limitations.
# Task 05: Traffic Accident Analysis & Visualization  

## Dataset  
**US Accidents Dataset (March 2023)** — `US_Accidents_March23.csv`  

## Objective  
To analyze and visualize **traffic accident patterns** in the US to understand **temporal, environmental, and location-based factors** contributing to accidents.  

## Steps Performed  
- **Loaded and combined dataset** in chunks for memory efficiency  
- **Cleaned data** by handling missing values in `Start_Time`, `Start_Lat`, and `Start_Lng`  
- **Extracted additional features:** `Hour` of day and `DayOfWeek`  
- **Analyzed accidents** by:  
  - **Hour of day**  
  - **Day of week**  
  - **Severity level**  
  - **Weather conditions**  
- **Visualized patterns** using **bar charts, count plots, and heatmaps**  
- Generated an **interactive heatmap** of **accident hotspots** using **Folium**  

## Tools Used  
- **Python**  
- **Pandas**  
- **Matplotlib**  
- **Seaborn**  
- **Folium**  

## Key Insights  
- Accidents **peak during rush hours**, especially **mornings and evenings**  
- **Weekdays (Monday–Friday)** show higher accident frequency  
- Weather conditions like **Rain, Snow, and Low Visibility** increase accident risk  
- Heatmaps highlight **high-risk zones across the US**  

## Deliverables  
- **Plots:** Temporal, severity, and weather-related accident visualizations  
- **Interactive Map:** Heatmap of **accident hotspots** (`accident_hotspots.html`)  
