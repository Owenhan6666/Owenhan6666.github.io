---
name: visualizations
tools: [Python, HTML, Vega-Lite]
image: assets/pngs/visualizations.png
description: This is an engaging "showcase" project that utilizes Vega-Lite for dynamic and interactive visualizations!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

## Building Year Histogram

<iframe src="{{ site.baseurl }}/visualizations/building_year_histogram_improved.html" width="100%" height="500px" frameBorder="0"></iframe>

This visualization shows the distribution of building construction years in the dataset...

## Total Square Footage per Agency

<iframe src="{{ site.baseurl }}/visualizations/total_square_footage_per_agency.html" width="100%" height="500px" frameBorder="0"></iframe>

This visualization shows the total square footage of buildings owned by each agency...

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="link-to-your-jupyter-notebook" text="The Analysis" %}
</div>
