# Project 2 Open Data NYC
https://barglary.shinyapps.io/FINAL_project/

https://github.com/MarkEdmondson1234/shinyga

https://github.com/imbenzene/healthrank/

https://crimeradar.shinyapps.io/final_project/

In this second project of W4249 Applied Data Science, we will carry out *Exploratory Data Analysis and Visualization* via a shiny app on a topic about open data released from the [New York City open data portal](https://nycopendata.socrata.com/). See [Project 2 Description](project2_desc.md) for more details.  

The learning goals for this project is 
- exploratory data analysis
- visualization
- shiny app
- app production work flow

This repo has been organized as follows.
```
proj/
├── lib/
├── data/
├── doc/
├── app/
└── output/
```
![screenshot](doc/screenshot2.png)

Barglary(Project 2) - Team 7

Team members: Aoyuan Liao, Rong Wang, Arnold Chua Lau, Yanran Wang, Haoyang Chen  

Summary: In this project, we visualized the geographic distribution of crimes in NYC and tried to find a relation between crime occurance and geographic positons. We built an app to help users find the safest bar located in a neighborhood with low crime rate and this app also provide other information about bars such as their address, the commonest type of crime in their neighborhood and their rankings in NYC.

Aoyuan Liao did the following:
* Designed and developed the shiny app including bar searching box, neighborhood searching box, crime type selecting box and time slider bar.
* Marked bars' location on Leaflet choropleth map with different marking symbols.
* Embedded Google Maps API and marked the location of the bar that users search for on Google map.

Arnold Lau did the following:
* Sourced and processed crime and liquor license data
* Converted raw data into spatially-referenced data via merging with NYC Neighborhood Tabulation Areas
* Designed and developed the shiny app including bar searching box, neighborhood searching box, crime type selecting box and time slider bar.
* Created Leaflet choropleth map for crime density.

