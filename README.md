# The economic and population effect of storm events

## Synopsis
The following report studies the economic and population effect of storm events from November 1950 to 2011. It presents its conclusion on Tornado being the storm event that has the greatest impact on population health, being responsible for 5,633 deaths throughout the observational period. It also observe that catastrophic-but-rare events such as tornadoes, thunderstorm wind and hurricane does great damages to property and crops on a per-event basis, but overall have lesser economic consequences than frequent weather events such as flood, which alone has caused an astounding 150.32 billion USD in economic losses between 1950 to 2011.

## Files Structure
- The raw data is provided as a CSV file from the NOAA website, named "StormData.csv"
- The script and analysis itself is a R Markdown document, named "Analysis.Rmd"
- Analysis.html is the file we knitted using Sweave, a copy of it is published on Rpub

## Pre-requisites
- The only external library we use is ggplot2. 
- Original dataset: [Storm Events Database](https://www.ncdc.noaa.gov/stormevents/)

## Analysis
The analysis is made up of the following sections:
1. Synopsis: A simple summary of the research
2. Data Processing: Where we clean the data and process the data for analysis
3. Results
3.1 Analysis 1: Types of storm events that are most harmful with respect to population health
3.2 Analysis 2: Types of events that have the greatest economic consequences over the course of 1950 to 2011
3.3 Analysis 3: Types of events that, on average, causes the most potent economic damages 
4. Further Observations and Recommendations
5. Appendix

