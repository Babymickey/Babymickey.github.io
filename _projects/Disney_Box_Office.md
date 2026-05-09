---
layout: post
title: "80 Years of Disney Box Office Magic"
name: "80 Years of Disney Box Office Magic"
author: "Mickey Felton"
image: assets/pngs/images.jpg
description: "Exploring 80 years of box office trends"
show_tile: true
---
<script src="https://cdn.jsdelivr.net/npm/vega@5"></script>
<script src="https://cdn.jsdelivr.net/npm/vega-lite@5"></script>
<script src="https://cdn.jsdelivr.net/npm/vega-embed@6"></script>


# 80 Years of Disney Box Office Magic
**Group: Mickey Felton**

### Introduction: Why do we care about the Mouse?
Since the release of Snow White in 1937, Disney has transitioned into a media powerhouse. This transition is clearly visible when looking at Disney Movie Box Office data over the last 30 years. In the beginning, Disney releases were sporadic, then there was a boom in movies during the Disney Renaissance Era. As Disney found its formula for movies and acquired big-name franchises such as “Avengers”, it has reached unprecedented heights. This interactive chart allows you to explore every major release and filter by genre to see how Disney’s output has increased in the 21st century.


### Evolution of Disney
The scatter plot below serves as our primary evidence for Disney's growth. Each dot represents a gamble. By using the genre filter, you can see that while Disney was once a "Musical" factory, their strategy shifted toward "Action" and "Adventure" as the 21st century approached. This isn't accidental; as production costs rose, Disney narrowed its focus onto genres with the highest global appeal.

{% include vegachart.html path="assets/json/main_color_chart.json" %}


### Contextualizing Success: Genre vs. Market
To address why Disney dominates, we have to look at their "hit rate" per genre. In the chart below, notice that **Adventure** and **Action** have the highest average gross. However, when we look at context data from the wider film industry, we find that Disney's Adventure movies actually gross 40% more than the industry average for that same genre. This tells us that the "Disney Brand" adds a value that a standard studio movie doesn't have.

{% include vegachart.html path="assets/json/genre_color_chart.json" %}


### The Impact of Renessiance Era?
The "Renaissance Era" (1989-1999) is often called a miracle, but was it? In the chart below, we see the top hits like *The Lion King*. To add context, during this same decade, the total global box office was growing at 10% per year. Yet, Disney’s revenue grew at **nearly 25% per year**. This proves that while the "tide was rising" for all of Hollywood, Disney was building a much bigger boat. They weren't just lucky; they were outperforming the entire market.

{% include vegachart.html path="assets/json/renaissance_color_chart.json" %}

###Box Office Hits vs Disney
By comparing Disney's hits against the Top 25 industry successes of the same era, we can see if Disney movies are outliers or if they simply follow the general box office curve. This chart helps distinguish between a 'good year for movies' and a 'great year for Disney'.

{% include vegachart.html path="assets/json/boxoffice_color_chart.json" %}

### Conclusion: Key Findings
Our analysis reveals three main truths:
1. **Genre Pivot:** Disney's move from Musicals to Adventure was a calculated financial shift to capture the global 21st-century market.
2. **The Brand Premium:** Disney movies consistently outperform industry-average benchmarks in the same genres.
3. **Renaissance Dominance:** The 1990s weren't just a good time for movies; they were a decade where Disney's creative output fundamentally outpaced the growth of the rest of Hollywood. 

Through these datasets, it’s clear that Disney’s "Magic" is backed by a very disciplined, data-driven strategy of genre dominance.
---
**Data Sources:** [Disney Movies Dataset via Data.World](https://query.data.world/s/q6d4wfxrzhpcxwurhr5ly6hv7vb7ti?dws=00000)  
**Contextual Visualizations:** These charts were created by the author using the primary Disney dataset and A Box Office Hits Dataset [Box Office Hits Dataset via Kaggle/Github](https://raw.githubusercontent.com/kalilurrahman/BoxOfficeData/main/boxofficemojoustop1000.tsv)
**Analysis Notebook:** [View the Python Analysis Notebook on GitHub](https://github.com/Babymickey/Babymickey.github.io/blob/main/python_notebooks/disney.ipynb)
