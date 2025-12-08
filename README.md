Project Overview
This project is an interactive data analytics dashboard designed to monitor global weather patterns, environmental risks, and atmospheric conditions. It transforms raw meteorological data into actionable insights, helping users visualize the relationship between temperature, pollution, and public safety.

Technology Stack
Data Processing: Python (Pandas) for data cleaning, type conversion, and handling missing values.

Visualization: Microsoft Power BI for creating interactive reports and dynamic dashboards.

Analytics: Custom DAX measures for calculating averages, maximums, and dynamic labels.

Data Source: Global weather dataset containing metrics like temperature, humidity, PM2.5, and UV index.

Dashboard Structure & Key Features
Page 1: Overview Analysis

Provides a high-level summary of global climate conditions.

Key Visuals:

KPI Cards displaying real-time averages for Temperature, Wind, and Humidity.

Global Map visualizing temperature distribution across different regions.

Combo Chart tracking Average Temperature vs. Precipitation levels.

Page 2: Detailed Analysis

Focuses on correlations and meteorological trends to identify weather anomalies.

Key Visuals:

Correlation Heatmap: Analyzes the density relationship between Temperature and Humidity (Hotter climates = Drier air).

Wind Dynamics: A Treemap visualizing wind intensity across different weather conditions.

Storm Predictor: A dual-axis line chart comparing Atmospheric Pressure vs. Maximum Wind Speed to identify storm risks.

Page 3: Environmental Impact & Health

Examines how weather factors affect human health and environmental safety.

Key Visuals:

Air Quality Status: A Donut chart categorizing locations by air quality index (Good vs. Hazardous).

Pollutant Breakdown: A Stacked Bar chart identifying primary pollutants (PM2.5, NO2, Ozone) by country.

Solar Trends: An Area chart tracking Seasonal UV Intensity to assess solar radiation risks over time.

Key Analytical Insights
Temperature vs. Humidity: There is a strong inverse correlation; regions with temperatures above 30°C consistently show humidity levels below 20%.

Storm Forecasting: A sharp drop in atmospheric pressure (<1000 mb) serves as a reliable precursor to high wind spikes, acting as an early storm warning.

Pollution Impact: Analysis confirms a direct negative correlation between PM2.5 levels and visibility, with significant visibility drops observed during winter months due to smog accumulation.

How to Run
Open the .pbix file in Microsoft Power BI Desktop.

Ensure the data source path is correctly linked to the processed CSV file.

Use the slicers on each page to filter the analysis by Country, Year, or Weather Condition.