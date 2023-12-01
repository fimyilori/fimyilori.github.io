---
name: Fimy Ilori HW 8
tools: [Python, HTML, vega-lite]
image: assets/pngs/plot1.png
description: IS 445 HW #8 
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Interactive Plot of Year Constructed and Total Floors

Plot and Analysis of first plot


 





<vegachart schema-url="{{ site.baseurl }}/assets/json/visualization.vl (1).json" style="width: 100%"></vegachart>

In the code, we are visualizing a subset of building inventory data from the dataset. The primary goal is to explore the relationship between the year a building was constructed (Year Constructed) and the number of total floors (Total Floors). We're interested in understanding how the construction year relates to the building's height, represented by the number of floors, and whether there are any patterns or trends in this relationship. I used Altair to create a scatter plot with some specific encoding types. The x-axis is encoded using "Year Constructed," treated as a temporal variable, as it represents a specific year. The y-axis represents "Total Floors" is a quantitative variable since it involves numerical counts. I also utilized a color encoding for the points based on the "Total Floors" variable, allowing us to visually differentiate buildings with varying heights. This choice of color scheme helps highlight the distribution of buildings across different height categories. On the analysis side, I applied data transformations by loading the dataset from the provided URL. Due to the dataset's size, I selected a random subset of 5000 rows to ensure the visualization creation is within the default row limit of Altair. This step allowed us to work with a manageable portion of the data for plotting without hitting any restrictions. The color encoding used in the chart adds an additional layer of information, helping viewers discern the building's height and providing insights into how the total number of floors varies with the year of construction.



<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="The Data" %}
</div>



<div class="right">
{% include elements/button.html link="https://github.com/fimyilori/fimyilori.github.io/blob/main/python_notebooks/Workbook.ipynb" text="The Analysis" %}
</div>



# Plot of Building Status and Congressional District 





<vegachart schema-url="{{ site.baseurl }}/assets/json/visualization.vl.json" style="width: 100%"></vegachart>



For this visualization I am focusing on two specific variables: "Building Status" and "Congressional District." I chose to use a bar chart to represent the data because I thought that would be the easiest to show the status of buldings in different congressional districts. I wanted to show these two specific variables because you can infer that the districts that have more abandoned buildings are most likely more prone to homelessness so I thought this would be a good way to show this. The color encoding was not used in this chart. Instead, the main focus was on comparing the distribution of building statuses across different congressional districts. The choice of a bar chart is suitable for this task as it provides a clear view of the count or frequency of each building status within each congressional district.


####  Design

For the design of the plots I wasn't too focused on the color scheme but I just chose to do blues because it seemed the simplest. Both Plots use Altair to create the plot



<!-- these are written in a combo of html and liquid - --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/fimyilori/fimyilori.github.io/blob/main/python_notebooks/Workbook.ipynb" text="The Analysis" %}
</div>



