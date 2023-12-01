---
name: Final Project 3
tools: [Python, HTML, vega-lite]
image: assets/pngs/Crime1.jpeg
description: IS 445 Final Part 3.1 
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Description of crimes by Location (Latitude and Longitude) in Rockford Illinois 2011-Present

Plot and Analysis of first plot


 





<vegachart schema-url="{{ site.baseurl }}/assets/json/visualization.vl (1).json" style="width: 100%"></vegachart>

<vegachart schema-url="{{ site.baseurl }}/assets/json/visualization.vl (1).json" style="width: 100%"></vegachart>

## At least one central interactive visualization featuring your primary dataset. 

There are two plots for our visualization that feature our primary dataset. The first plot titled “Crime Analysis by Day of the Week” is an analysis of crimes that occurred at a specific location displayed by Latitude and Longitude. You are able to select what day of the week you want to see the crime, and where it happened. The second plot shows the same Latitudinal and Longitudinal coordinates of crimes that happened in Rockford. A new feature however, is the ability to select what “Ward” that the person was assigned to and shift between 14 of them using a slider. The slide also changes the plot to only show people assigned to that specific ward or range or wards.

## At least two contextual visualizations

https://police.illinois.edu/info/map/

https://www.opendatanetwork.com/entity/1600000US1712385-1600000US1805860/Champaign_IL-Bloomington_IN/crime.fbi_ucr.count?crime_type=Aggravated%20assault&year=2018

## Connective information to help a novice understand what is happening in your datasets

The datasets that we chose to use all concern the police incidents and crimes that have happened over a set period of time in the respective cities of Rockford (IL), Urbana (IL), and Bloomington (IN). We chose to use these datasets because they are all similarly-sized cities so we wanted to see a comparison of how much crime occurs in these cities and if there are any correlations such as the days the crimes occur, and what types of crimes are most common, just to name a few. 

In our primary dataset, which shows the crime offenses from 2011-Present in the city of Rockford, IL, we are presented with a lot of information and data that helps put into perspective the amount of crime offenses that have happened over the past 12 years. Some of the rows that we are presented with within the dataset are The case number, the description of the crime, the date, the day of the week, and the time that the crime occurred, the longitude and latitude of where the crimes occurred, as well as the police ward that the crime occurred in among a few others. Within the dataset, you are able to sort by the different rows, for example, one could sort by the day of the week to see what days of the week had the most crimes occur, additionally, you are able to add filters if you wanted to exclude a certain row. 

One of our contextual datasets is a crime map of the crime incidents in the Campustown area of the University of Illinois. The dataset includes the crime map which is the main visualization used within the dataset. Within the crime map, there are different colored points on the actual map. The red points show the most recent crimes that have occurred in Campustown, while the green points show the least recent crimes that have occurred, with the blue points being in the middle. There is also a legend and two different interactive filters on the map, the recency of the crime and the time of day in which the said crimes occurred. 

Our third dataset shows the crime incidents that have occurred in Bloomington, IN, from 2003-2018. The rows within the dataset are as follows, the crime incident count, the crime incident count per 100,000 people, the type of crime that was committed, and the year in which the crime was committed. Additionally, the dataset also shows the total number of crimes that were committed in each year that is included in the dataset (2003-2018). There is also a bar graph visualization of the crime incidents by year in which you can change the year to see visually the total amount of each type of crime committed in a certain year. 


## Citations of all the data sources used and information for the reader to be able to find those datasets themselves

Yu, Aaron, et al. “Crime Map.” Public Safety, 26 June 2023, police.illinois.edu/info/map/. 

“Crime Incident Count for Champaign and Bloomington.” Open Data Network, www.opendatanetwork.com/entity/1600000US1712385-1600000US1805860/Champaign_IL-Bloomington_IN/crime.fbi_ucr.count?crime_type=Aggravated+assault&amp;year=2018. Accessed 30 Nov. 2023. 


<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="The Data" %}
</div>



<div class="right">
{% include elements/button.html link="https://github.com/fimyilori/fimyilori.github.io/blob/main/python_notebooks/Workbook.ipynb" text="The Analysis" %}
</div>




