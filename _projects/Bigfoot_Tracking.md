---
name: Bigfoot Sightings Analysis
tools: [Python, Altair, vega-lite]
image: assets/plots/bigfoot_preview.png
description: An interactive look at Bigfoot sightings across the US by season.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

# Bigfoot Sightings: A Seasonal Analysis

### Analysis of Visualization 1
This chart visualizes Bigfoot sightings by state and season. I wanted to show which states have the most activity and identify seasonal patterns. I used **Nominal** encodings for the state and season categories and **Quantitative** encodings for the record counts. I utilized Altair's internal aggregation to calculate these counts directly from the raw data.

<vegachart schema-url="/assets/json/bigfoot_chart.json" style="width: 100%"></vegachart>

### Analysis of Visualization 2
This chart visualizes sightings by geographical location (longitude and latitude) categorized by season. This spatial view shows which specific regions have the highest density of reports. I used **Quantitative** encodings for the geographic coordinates and **Nominal** encodings for the seasons. I used the default color scheme to keep seasons distinct.

<vegachart schema-url="/assets/json/bigfoot_chart_inter.json" style="width: 100%"></vegachart>

### Interactivity Discussion
For the second chart, I implemented a dropdown menu for seasons. Since the dataset is large, this allows the user to filter the points to see only a specific season at a time, making the visualization much clearer and easier to understand.

## The Data & Methods

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/bfro_reports_fall2022.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/Babymickey/Babymickey.github.io/blob/main/Bigfoot_Analysis.ipynb" text="The Analysis" %}
</div>
