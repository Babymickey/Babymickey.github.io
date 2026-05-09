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


### Disney Box Office Success
Have you ever wondered how Disney has evolved from a small animation house to a box office giant? I have. Since the release of Snow White in 1937, Disney has undergone a major transformation. While the "Disney Renaissance Era" is credited for this, the real story lies in how the studio shifted it focus to dominate the modern era.

<br>
### From Variety to Velocity: The Strategic Pivot
To understand this evolution, we can first look at the sheer volume and timing of their releases. In the early years, Disney's release schedule was sporadic and lacked a clear genre identity. However as we approached the 21st century, the "scatter" in the data began to cluster. Disney began focusing on Adventure and Action. This wasn't accidental, it was a strategic move to capitalize on genres with the highest global "repeat-watch" appeal and merchandising potential.

{% include vegachart.html path="assets/json/main_color_chart.json" %}

<br>
### Why Adventure and Action? Follow the Money
The pivot raises the questions: Why has this genre focus occurred? The answer can be found in the revenue. When we look at average gross income per genre, the data reveals a massive performance gap.   Adventure and Action don't just perform better; they earn in a different class compared to the next genres, Musical and Comedy.

{% include vegachart.html path="assets/json/genre_color_chart.json" %}

<br>
### The Impact of Disney Renaissance Era?
The "Renaissance Era" (1989-1999) is often called a creative miracle. But the numbers suggest it was a lesson in market performance. During this decade, the global box office grew at a healthy 5%. Yet, Disney's revenue skyrocketed at nearly 15%. Hits like *The Lion King* and *Toy Story 2* proved that while the box office was growing for everyone, Disney was showing to be a much bigger powerhouse. They didnt just ride the wave of the decade, they owned it.

{% include vegachart.html path="assets/json/renaissance_color_chart.json" %}

<br>
### Disney vs. The Giants: 1943-2021
Finally, we must ask if Disney’s hits are simply outliers or if they follow the general success of the era. To find out I pulled the Top 25 movies from 1943-2021, comparing the number of Disney successes to other industry successes. For example if you look specifically at Disney's adventure catalog compared to all the Top 25, the results are startling. While one might expect a single studio’s average to be dwarfed by an all-time ‘Best Of’ list, Disney’s Adventure catalog averages $127 million—only 22% behind the Top 25 industry average of $163 million. 
When you consider that the Top 25 includes the biggest blockbusters ever made (like *Avatar, Star Wars, Avengers and Titanic), the fact that Disney’s average movie performs so close to the industry’s peak highlights their massive brand power. This confirms that a standard Disney adventure is often a "massive hit" for anyone else.  

{% include vegachart.html path="assets/json/boxoffice_color_chart.json" %}

<br>
### Conclusion: The Science Behind the Magic
Our analysis reveals three main truths about the "Magic" of the Disney:
1. **Strategic Pivot:** Disney's move from unfocused genres releases to leaning toward Adventure and Action was a calculated financial shift to capture the global 21st-century market.
2. **The Brand Premium:** Disney movies consistently outperform industry-average benchmarks in the same genres, showing the power of their intellectual property.
3. **Renaissance Dominance:** The 1990s were a period where Disney's creative output fundamentally outpaced the growth of the rest of Hollywood, allowing them to become the giant they are today..

Through these datasets, it’s clear that Disney’s dominance is the result of a disciplined, data-driven strategy of genre dominance and brand leverage.

---
**Data Sources:** [Disney Movies Dataset via Data.World](https://query.data.world/s/q6d4wfxrzhpcxwurhr5ly6hv7vb7ti?dws=00000)  
<br>
**Contextual Visualizations:**  These charts were created by the author using the primary Disney dataset and A Box Office Hits Dataset [Box Office Hits Dataset via Kaggle/Github](https://raw.githubusercontent.com/kalilurrahman/BoxOfficeData/main/boxofficemojoustop1000.tsv)
<br>
**Analysis Notebook:** [View the Python Analysis Notebook on GitHub](https://github.com/Babymickey/Babymickey.github.io/blob/main/python_notebooks/disney.ipynb)
