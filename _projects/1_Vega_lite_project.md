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


# Plot 1

Plot and Analysis of first plot


## 





<vegachart schema-url="{{ site.baseurl }}/assets/json/visualization.vl (1).json" style="width: 100%"></vegachart>


This bar chart simply shows how often different Congressional appear in our dataset. Each bar corresponds to a Congressional Name, giving us a quick snapshot of how many buildings were built under which congressmen. This can help people understand the work and impact of different congressman. I have used both quantitative and ordinal encoding. People can really understand the infrastructural growth under each congressman


To keep things clear, I used a straightforward design. The x-axis tells us how many times each name shows up (that's the count), and the y-axis lists the Congressional Full Names. It's like a tally chart, but in a visual form.


I skipped using fancy colors to keep it neat and focused. The idea is to make it easy for you to see which names pop up more without any unnecessary distractions.


On the coding front (you can check it my analysis notebook), I used a basic trick to count how many times each Congressional Full Name appears in the dataset. This way, we get a clean and simple bar chart that tells us at a glance which Congressional Names have gotten the most buildings constructed compared to all other



<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="The Data" %}
</div>



<div class="right">
{% include elements/button.html link="https://github.com/Samridhiverma27/Samridhiverma27.github.io/blob/main/python_notebooks/HW8-IS445.ipynb" text="The Analysis" %}
</div>



## Interactive plot on Usage Description and Square Footage of it





<vegachart schema-url="{{ site.baseurl }}/assets/json/interactive_bar_chart.json" style="width: 100%"></vegachart>



This interactive bar chart tells us more about 'Usage Description,' providing insights into the distribution of various usages such as Storage, Assembly, Industrial, Health Care, Business, Education, Mercantile, Residential, Detention & Correc, Utility & Miscellaneous, and Public VS the average square feet (how much space does it utilise on an average). This can particularly help people understand how the government is building infrastructure, how much space do different types of usage need and can also help justify their budgets and costs.

#### Encodings

I have used Quantitative encoding for the 'average(Square Footage)' on the y-axis, Ordinal encoding for the 'Usage Description' on the x-axis, and Nominal encoding for color representation based on the 'Usage Description'.

#### Plot Axis

The x-axis represents these distinct usage descriptions, and the y-axis showcases the average square footage associated with each usage. The chart is designed to be user-friendly and visually informative, allowing users to explore and compare average square footages across different building usages.

For the interactive part, I implemented a dropdown menu where Users types and can get a precise number of avg square footage for a specific usage from the list/ This can help people get a comparision on square foot and usage averages as well get a concise number on its usage and size per square feet. Scale on the main comparator graph is too big and hence having an option to view concise averages of any particular usage category can be really helpful

####  Design choices

In terms of design, each bar is color-coded based on the respective usage description, aiding users in quickly distinguishing between different categories.

This interactive exploration leverages Altair's selection and transformation capabilities, allowing users to interact with the data and gain insights in a more engaging and dynamic manner.



<!-- these are written in a combo of html and liquid - --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/Samridhiverma27/Samridhiverma27.github.io/blob/main/python_notebooks/HW8-IS445.ipynb" text="The Analysis" %}
</div>

## Overlap from Homework 7

There is not visualization overlap from homework 7, I have made new visualizations for this part of the assignment. 

