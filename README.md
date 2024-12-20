# Project ESG Dashboard (Tableau)

## The idea of the project
The idea of the project is to create a dashboard in which we could analyze ESG country data. We would like to be able to compare different countries and different indicators. Find out whether there are any correlations between the size of the countries and the performance of the countries.

## Data:
- Provided by World Bank
- Rows: 16,969
- Columns: 68
- Some data is missing
- Years: 1960-2023

## Cleaning (file: data_cleaning.ipynb)
- Used libraries: pandas

## Looking at the data and deciding which years and countries to keep for the dashboard
- I have decided to keep the years after 1998 for more relevant data.
- Modified the data shape to long format because each year was a separate column.
- Ended up with 5 columns.
- Kept only the countries/regions of interest (the ESG report had also regional data).
- Checked for indicators that I had to remove if they were completely empty.
- Removed missing values.

## Link to the dashboard in Tableau:
[View Dashboard](https://public.tableau.com/app/profile/gabriela.arlt/viz/WorlESGAnalysis/FirstDashboard)

## Features of the Dashboard:
- In my Dashboard, I have compared three countries and how they perform with regards to different indicators: Bulgaria, Spain, and Germany. You can take a look at the final section of the dashboard.
- I have divided the indicators into three groups: social, economic, and environmental.
- Each group has its own section in the dashboard. Users can choose a specific country, year, or indicator to observe trends or world performance.
- Users can compare high-income countries to low and middle-income countries, or choose a country of their choice.
- Users can also choose three different countries for comparison.
- Last but not least, we can check the correlation between different indicators.

## Add your country and enjoy the ride!
