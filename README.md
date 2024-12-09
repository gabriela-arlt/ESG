
# Project:  ESG Dashboard (Tableau)
## The idea of the project is to create a dahsboard in which we could analyze ESG country data. We would like to be able to compare different countries and different Indicators. Find out whether there is any correlations between the size of the countries and the performance of the countries.

## Data:
+ Porvided by World Bank
+ rows: 16969
+ columns: 68
+ some data is missing
+ years 1960- 2023
## Cleaning (file: data_cleaning.ipynb)
+ used libaries: pandas
## Looking at the data and deciding which years and countries to keep for the dashboard
+ I have decided to keep the years after 98 for more relevant data
+ Modification of the data shape to long because each year was a separate column
+ Ended up having 5 columns
+ I kept only the countries/regions in my interest (the ESG report had also regional data)
+ Checked if there are indicators which I had to remove if they are completely empty
+ removed missing values
## Link to the dashboard in Tableau: https://public.tableau.com/app/profile/gabriela.arlt/viz/WorlESGAnalysis/FirstDashboard

+ In my Dashboard I have compared three countries and how they perform in regards to different indicators: Bulgaria, Spain and Germany. You can take a look at the final section of the dashboard.
+  I have divided the indicators into three groups : social, economical and environmental
+  Each groups has its own section in the dashboard. Users can choose a specific country, year or indicator in order to observe trends or world performance
+  Users can compare High income countries to Low and Middle income or country of their choice
+  Users can also choose three different countries for comparison
+  Last but not least we can check the correlation between dofferent indicators
## Add your country and Enjoy the ride!

 
 
