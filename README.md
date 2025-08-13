# US Accidents Analysis

## Overview
This project analyzes the **US Accidents** dataset to uncover patterns, trends, and insights related to traffic accidents across the United States. The dataset contains millions of accident records with features like location, weather conditions, time, and severity.

The analysis is performed in Python using Jupyter Notebook: **us-accidents-analysis.ipynb**.

## Objectives
- Explore and understand the dataset.
- Perform exploratory data analysis (EDA) to detect patterns and correlations.
- Visualize accident trends over time and across geographic locations.
- Identify environmental and temporal factors that influence accident severity.
- Generate insights that can support road safety initiatives.

## Dataset
- **Source:** US Accidents (2016–present) dataset (commonly available on Kaggle).
- **Size:** Millions of rows with accident records.
- **Key Columns:** `ID`, `Severity`, `Start_Time`, `End_Time`, `Start_Lat`, `Start_Lng`, `City`, `State`, `Temperature(F)`, `Weather_Condition`, `Visibility(mi)`, `Wind_Speed(mph)`.

## Tools & Libraries
- `pandas` – data manipulation
- `numpy` – numerical computations
- `matplotlib` & `seaborn` – visualizations
- `plotly` – interactive plots
- `folium` – geospatial mapping
- `datetime` – time-based analysis

## Analysis Workflow
1. **Data Loading & Cleaning**
   - Import dataset.
   - Handle missing values and duplicates.
   - Convert time columns to proper datetime format.

2. **Exploratory Data Analysis**
   - Accident counts by year, month, day, and hour.
   - Severity distribution analysis.
   - Top states and cities by accident count.
   - Weather condition impact on accidents.

3. **Geospatial Analysis**
   - Mapping accidents across the US.
   - Identifying hotspots using clustering and heatmaps.

4. **Correlation Analysis**
   - Analyzing how weather, visibility, and wind speed affect accident severity.

5. **Visualization**
   - Heatmaps, bar charts, line plots, scatter plots.
   - Interactive geospatial visualizations.

## Key Insights
- Most accidents occur during **rush hours** (7–9 AM and 4–6 PM).
- **California, Texas, and Florida** report the highest accident counts.
- Adverse weather (fog, rain, snow) correlates with higher severity.
- Urban areas have more accidents than rural areas.
- Poor visibility and high wind speeds increase accident risk.

## Running the Notebook
1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly folium
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook us-accidents-analysis.ipynb
   ```
3. Run the notebook cells sequentially.

## Future Enhancements
- Implement machine learning models for severity prediction.
- Real-time accident data integration.
- Advanced geospatial clustering for hotspot detection.



