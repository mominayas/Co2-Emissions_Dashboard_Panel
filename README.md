# Co2-Emissions_Dashboard_Panel
An interactive dashboard visualizing CO2 emissions data over time using Python, Panel, and Pandas. Includes four visualizations: CO2 emissions by continent, a data table, a CO2 vs. GDP scatterplot, and a CO2 source bar chart. The dashboard features interactive widgets for dynamic data exploration from 1750 to 2020.

## Visualizations

The dashboard contains the following visualizations:

1. **CO2 Emissions Over Time by Continent**: A line chart that shows the CO2 emissions or CO2 emissions per capita for different continents over time. Users can adjust the year range with a slider and select the CO2 measure using radio buttons.

2. **CO2 Emissions Data Table**: A table displaying CO2 emissions data over time by continent. The table supports remote pagination and allows users to view data in a structured format.

3. **CO2 vs. GDP Scatterplot**: A scatterplot visualizing the relationship between CO2 emissions and GDP per capita for various countries in a selected year. Users can explore how CO2 emissions correlate with economic performance.

4. **CO2 Emissions by Source (Bar Chart)**: A bar chart representing CO2 emissions from different sources (coal, oil, gas) for each continent (excluding Antarctica). Users can select the source of CO2 emissions to view specific data.

## Features

- **Interactive Widgets**: Year slider, radio buttons for selecting CO2 measures and emission sources.
- **Data Filtering and Grouping**: Dynamic filtering and grouping of data for tailored visualizations.
- **Responsive Layout**: Adjusts to different screen sizes for optimal user experience.
- **Built with Modern Python Libraries**: Utilizes Panel for dashboard creation and Pandas for data manipulation.

## Requirements

To run the dashboard, you need the following libraries:

- `pandas`
- `panel`
- `hvplot`

You can install these dependencies via pip:

```bash
pip install pandas panel hvplot

##Run Dashboard
panel serve --show co2_dashboard.py



## Clone the repository
git clone https://github.com/mominayas/co2-emissions-dashboard.git
cd co2-emissions-dashboard
