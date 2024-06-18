### README.md

# Analyzing the Relationship Between Air Quality Index (AQI) and Asthma Outcomes Across Counties

## Project Overview

This project investigates the relationship between Air Quality Index (AQI) levels and various asthma outcomes across counties. The study uses multiple visualizations created in Tableau to identify areas and populations most affected by poor air quality. The visualizations include heatmaps, triple combination charts, tree maps, point maps, and grouped bar charts.

## Repository Structure

-   **/data**: Includes both raw and processed datasets used in the analysis.
-   **/docs**: Contains additional documents such as the final paper and supplementary figures.
-   **/workbooks**: Contains all Tableau workbooks used for creating visualizations.

## Prerequisites

To view and interact with the visualizations, you need to have Tableau Desktop (version 2021.1 or later) installed.

## Data Sources

1. **AQI Data**: Collected from the Environmental Protection Agency (EPA) database.
2. **Asthma Data**: Sourced from county health departments.

## Instructions

### 1. Importing Data into Tableau

The cleaned datasets are saved in the `/data` directory. Open Tableau Desktop and connect to these datasets.

### 2. Opening Tableau Workbooks

The Tableau workbooks for each visualization are provided in the `/workbooks` directory. Open each workbook in Tableau Desktop and ensure the data connections are correctly mapped to the datasets in the `/data` directory.

#### Heatmap with Label Overlay

1. Open `heatmap_with_labels.twbx`.
2. Connect to the processed AQI and asthma data.
3. Ensure the geographic data (county locations) is correctly mapped.
4. Customize the visualization as needed.

#### Triple Combination Chart

1. Open `triple_combination_chart.twbx`.
2. Connect to the processed AQI and asthma hospitalization, ED visit, and mortality data.
3. Adjust the chart settings to display bars for AQI levels and lines for asthma outcomes.

#### Tree Map

1. Open `tree_map.twbx`.
2. Connect to the processed demographic and asthma data.
3. Customize the tree map to display the demographic distribution of asthma cases.

#### Point Map

1. Open `point_map.twbx`.
2. Connect to the processed AQI and asthma mortality data.
3. Map the data points to counties, using size for mortality rates and color for AQI levels.

#### Grouped Bar Chart

1. Open `grouped_bar_chart.twbx`.
2. Connect to the processed AQI and asthma prevalence data.
3. Customize the chart to display bars for AQI levels and asthma prevalence by county.

### 3. Creating the Dashboard

1. Open `dashboard.twbx`.
2. Import all the individual visualizations into the dashboard.
3. Arrange the visualizations to create a cohesive and informative dashboard.
4. Add titles, legends, and tooltips to enhance usability.

### 4. Running the Project

After setting up the visualizations and dashboard, you can interact with the data to explore insights and trends. The dashboard provides a comprehensive view of the relationship between AQI levels and asthma outcomes across counties.

## Final Paper and Supporting Documents

The final paper, written in the IEEE VIS/VTGC format, is included in the `/docs` directory. The paper provides detailed explanations of the methods, results, and insights gained from the analysis.

## Limitations

-   Data on all demographics was not available.
-   AQI data was not available for every county.

## Contact Information

For any questions or issues, please contact the project lead, Hilda Ogamba, at [your email address].

## References

1. [EPA AQI Data](https://www.epa.gov/aqi)
2. [County Health Department Data](https://www.cdc.gov/asthma/)

---

This README provides a comprehensive guide to running the project, from data preprocessing to creating visualizations and dashboards in Tableau. The insights gained from this analysis can inform public health policies aimed at improving air quality and reducing asthma-related health issues.
# california-asthma-aqi-dashboard
