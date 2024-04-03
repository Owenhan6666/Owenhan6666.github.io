name: Building Visualization Project
tools:
  - Python
  - HTML
  - Vega Lite
image: assets/pngs/building_visualization.png
description: This project visualizes the distribution of building years and the total square footage per agency, leveraging the interactive capabilities of Vega Lite.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
---

# Building Visualization Project

This project visualizes the distribution of building years and the total square footage per agency, leveraging the interactive capabilities of Vega Lite. The visualization aims to provide insights into the age of buildings and the spatial distribution of agency properties.

We can use a vegachart HTML tag like so:

<vegachart schema-url="{{ site.baseurl }}/assets/json/building_year_histogram_improved.json" style="width: 100%"></vegachart>

<vegachart schema-url="{{ site.baseurl }}/assets/json/total_square_footage_per_agency.json" style="width: 100%"></vegachart>

In theory, you can also use Jekyll hooks to do it, but I haven't figured out a way that looks nice yet.

## Search The Data & Methods

Below is where we can put some links to both the data and the analysis code as buttons:

<div class="left">
{% include elements/button.html link="https://github.com/yourRepository/building_year_histogram_improved.json" text="Building Year Histogram Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/yourRepository/total_square_footage_per_agency.json" text="Total Square Footage Data" %}
</div>

{% include elements/button.html link="https://github.com/yourAnalysisCodeRepo" text="The Analysis" %}
