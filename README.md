# DATS6101-Project1

## Intro To Data Science EDA Project

This readme file is for planning about the project. We will draft out proposal here. The Data folder will hold potential data sets; its readme file will hold short descriptions of datasets.

We will upload our rmd files with EDA (if done) on these data sets. By Thursday, 9/29, we will arrive at strong candidates for our dataset.

At our Saturday 10/1 meeting, we decided on NOAA historical weather data for NYC set and preliminary question/s to include in the proposal (due 10/6).


## Project Description for Tejas, Chris, and Emily    

We propose to study weather trends in or around New York city over the past 100 years. We have found data from the National Oceanic and Atmospheric Administration (NOAA), via https://www.ncdc.noaa.gov/cdo-web, that include daily maximum and minimum temperatures, precipitation levels, and more for several different weather stations in or near the city.  

We are interested in several preliminary questions:  
1. Are there statistically measurable changes in weather patterns (e.g., temperature and precipitation levels) over time in New York City over this window?  
2. Are there any notable (and statistically significant) changes in weather patterns after/during the pandemic lockdown (perhaps due to changes in commuting patterns)?  
3. Do the observed changes in the weather data from New York City align with the documented rise in global air temperatures over the last century?  

We will begin with data from a weather station in Central Park (a total of ~36,500 observations over 100 years), and bring in data from additional NYC locations, other cities for comparison, or other weather or climate-related trends as we explore.

Our team’s Github repository is here: https://github.com/tejas-rawal/DATS6101-Project1
  

## Project plan & log

(Updated 10/9; can amend this as needed, as we go!)  

**Sunday, 10/9**  

Created an updated project plan  

1. This week, we'll all keep working independently on EDA in separate rmarkdown files, including to make visualizations that shed light on our questions, and think about what statistical tests we might apply. We'll add explanatory descriptions in our files.  
2. When we have chunks of analyses that we think are ready to share, we will copy them into a master Project file (can make branches) and create a pull request.  
3. We'll aim to knit the master (or in-progress individual) markdowns into html in advance of our 10/13 class.  


**Thursday 10/13 after-class meeting:**  
We'll meet after class for ~15 minutes to share/discuss our knitted file/s and potential statistical tests to explore, and discuss feedback from Prof. Morris if received.  

***Update:***  
We discussed our progress briefly during the class break.


**Saturday 10/15 Zoom meeting (2 PM):**  
We'll discuss (1) running any statistical tests and finalizing our project markdown file, making concrete assignments of what needs to be completed, (2) preliminary thoughts on how to present our project (and powerpoint).  

***Update:***  

Today we discussed our analyses to date and described our next steps:  
1. Emily will:  
  a. Do some more with linear regression of average monthly temperature over time for each month  
  b. Look at location of weather station and find another data set with a different type of city environment for comparison  
  c. Look into options for sine curve fitting of data for statistical comparison of fit parameters for difference (and ask Prof. Morris for feedback on this idea)  
  d. Just thought that the ANOVA test might work for March or April 2020 vs. March or April of 2019 & 2018, to get at question 2.  
2. Chris will   
  a. Focus on question 2 (pre- and post-pandemic differences) and question 3 (comparison to global trends over the same time period)  
  b. Start a google slide file with our three major questions, into which we can write our ideas for what analyses to be presented where.  
3. Tejas will:  
  a. Complete the outlier analysis (using ANOVA tests) for binned windows of 1900-1940 (industrial era) v 1940-1980 (cold war) v 1980-2020  
  b. Do additional research about pandemic lockdown dates and conditions toward addressing question 2, potentially creating a graphic to illustrate time frames  

We also agreed to meet on the evening of Tuesday, October 25 to practice our presentation.

**Sunday 10/23  Zoom meeting (2 PM):**  
We'll have our penultimate rmarkdown file and discuss any final tweaks needed prior to submission. We'll sketch out the power point presentation and assign sections to finalize and present.  

***Update:***  

**Tuesday 10/25  Zoom meeting (Time??):**  
We'll meet to practice our presentation and share feedback.

***Update:***

