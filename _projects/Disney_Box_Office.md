---
layout: post
title: "80 Years of Disney Box Office Magic"
name: "80 Years of Disney Box Office Magic"
Group: "Mickey Felton"
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
Since the release of *Snow White* in 1937, Disney has transitioned from a niche animation studio into a global media powerhouse. This evolution is most visible when looking at the box office data from the last 30 years. What began as a sporadic release schedule transformed into a dominant, formulaic boom during the "Renaissance Era," eventually leading to the acquisition of massive franchises like Marvel's *Avengers*, creating a media power house. 


### Evolution of Disney
To understand this rise, we can first look at the sheer volume and timing of their releases. The scatter plot below serves as my primary evidence for Disney's growth. Notice how the clusters change over time: while Disney was once without clear focus in movies, their strategy leaned toward "Action" and "Adventure" as the 21st century approached. This wasn't accidental; as production costs rose, Disney narrowed its focus onto genres with the highest global appeal.
{% include vegachart.html path="assets/json/main_color_chart.json" %}


### Success: Genre vs. Market
To address why Disney dominates, I compared the average gross of every Disney Adventure film against the Top 25 highest-grossing films in industry history. While one might expect a single studio's average to be dwarfed by an all-time 'Best Of' list, Disney's Adventure catalog averages $127 million—only 22% behind the Top 25 industry average of $163 million. When you consider that the Top 25 includes the biggest blockbusters ever made *(like *Avatar*, *Star Wars*, *Avengers* and *Titanic*), the fact that Disney's average movie performs so close to the industry's peak highlights their massive brand power.

{% include vegachart.html path="assets/json/genre_color_chart.json" %}


### The Impact of Renaissance Era?
The "Renaissance Era" (1989-1999) is often called a miracle, but was it? In the chart below, we see the top hits like *The Lion King*. To add context, during this same decade, the total global box office was growing at 5% per year. Yet, Disney’s revenue grew at **nearly 15% per year**. This proves that while the "tide was rising" for all of Hollywood, Disney was building a much bigger boat. They weren't just lucky; they were outperforming the entire market.

{% include vegachart.html path="assets/json/renaissance_color_chart.json" %}


### Box Office Hits vs Disney: 1943-2021
Finally, we must ask if Disney's hits are simply outliers or if they follow the general success of the era. By comparing Disney's top performers against the Top 25 industry successes of the same period, we can distinguish between a "good century for movies" and a "great century for Disney." As shown below, Disney movies often sit at the very top of the industry curve, cementing their status as market leaders rather than just participants.

{% include vegachart.html path="assets/json/boxoffice_color_chart.json" %}


### Conclusion: Key Findings
Our analysis reveals three main truths about the "Magic" of the Mouse:
1. **Strategic Pivot:** Disney's move from sporadic movie releases to leaning toward Adventure and Action was a calculated financial shift to capture the global 21st-century market.
2. **The Brand Premium:** Disney movies consistently outperform industry-average benchmarks in the same genres, showing the power of their intellectual property.
3. **Renaissance Dominance:** The 1990s were a period where Disney's creative output fundamentally outpaced the growth of the rest of Hollywood.

Through these datasets, it’s clear that Disney’s dominance is the result of a disciplined, data-driven strategy of genre dominance and brand leverage.

---
**Data Sources:** [Disney Movies Dataset via Data.World](https://query.data.world/s/q6d4wfxrzhpcxwurhr5ly6hv7vb7ti?dws=00000)  
**Contextual Visualizations:** These charts were created by the author using the primary Disney dataset and A Box Office Hits Dataset [Box Office Hits Dataset via Kaggle/Github](https://raw.githubusercontent.com/kalilurrahman/BoxOfficeData/main/boxofficemojoustop1000.tsv)
<br>
**Analysis Notebook:** [View the Python Analysis Notebook on GitHub](https://github.com/Babymickey/Babymickey.github.io/blob/main/python_notebooks/DISNEYv2.ipynb)
