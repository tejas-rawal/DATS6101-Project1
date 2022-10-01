# Data Descriptions

## DC_weather_2020-2022.csv
Contains a variety of weather observations for the DC area-- looks to actually be from weather stations in MD. Many of the values are NA!
Here is the site where I found weather data: https://www.ncdc.noaa.gov/cdo-web/
It seems to have additional data, for free download. It suggests records go back to the 1800s, but I'd guess most of the parameters' observations are NA.

## Bee Dataset
Geo-located occurrences of wild bees (superfamily Apoidea, clade Anthophila) in Maryland, Delaware, and Washington DC USA collected between 2002 and 2016 by the Native Bee Inventory and Monitoring Lab, United State Geological Survey. Data set is too large to upload to git, the download link here: https://figshare.com/articles/dataset/Mid-Atlantic_USA_wild_bee_occurrences_all_records/10266458.

Thought we could potentially pair it with another dataset for interesting correlations.

## World Development Indicators Dataset
This datasest comes from the the [World Bank Open Data portal](https://data.worldbank.org/).
- There are 100s of indicators listed here related to climate, economic health, energy, poverty, and more.
- The indicators can be explored [here](https://data.worldbank.org/indicator).
- They have more data that can be explore [here](https://databank.worldbank.org/databases)

#### Questions to explore
These are just some initial thoughts, but definitely open to discuss others!
1. Is economic stability correlated to increased (or decreased) emissions?
2. Compare GDP growth/decline to greenhouse gas emissions over last 10 years?
3. Compare health and/or economic indicators to environmental indicators such as greenhouse gas emissions, urban population, agricultural land?

## NYweath  
I found a more-complete data set for New York that incudes daily minimum temperatures, maximum temperatures, precipitation, and more. The file here includes data from 2020 to the current month-- additional data can be downloaded in batches (there is a size cap). Some initial trends are visible. The periodicity of temperatures with seasons are clear; would likely need to fit the data to a model before being able to draw conclusions about statistically significant changes in, e.g., temperature year-to-year. Could alternately look at, say, averages for a specific month and compare those year-to-year.

**Chris W Edit:** Uploaded the 1869-2022 version of this dataset. The file contains daily weather summaries to include the minimum & maximum temperatures, precipitation, and additional weather types. All records are collected from a Central Park weather station.

### Some ideas for exploratory questions  
1. Are there any statistically significant shifts in weather trends (temp, precip, wind) after the onset of COVID and initial lockdown (e.g., due to changes in large-scale travel patterns in/around the city)?  
2. When (under what conditions) is precipitation most likely in NYC (e.g., season, temperature, etc.) in a given year?  
