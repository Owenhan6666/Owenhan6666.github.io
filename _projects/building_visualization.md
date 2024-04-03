---
layout: project
title: "Building Visualization Project"
---

| name | tools | image | description | custom_js |
| --- | --- | --- | --- | --- |
| Building Visualization Project | Python, HTML, Vega-Lite || This project provides interactive visualizations of building years and total square footage per agency. | vega.min, vega-lite.min, vega-embed.min |

## Building Visualization Project

This is a showcase project that uses Vega-Lite for interactive visualizations! The visualization aims to offer insights into the construction years and square footage distributions of agency buildings.

We can use a Vega chart HTML tag like so:

```json
<vegachart schema-url="{{ site.baseurl }}/assets/json/building_year_histogram_improved.json" style="width: 100%;"></vegachart>
<vegachart schema-url="{{ site.baseurl }}/assets/json/total_square_footage_per_agency.json" style="width: 100%;"></vegachart>

<div class="left">
{% include elements/button.html link="https://github.com/yourRepository/building_year_histogram_improved.json" text="Building Year Histogram Data" %}
</div>
<div class="right">
{% include elements/button.html link="https://github.com/yourRepository/total_square_footage_per_agency.json" text="Total Square Footage Data" %}
</div>
{% include elements/button.html link="https://github.com/yourAnalysisCodeRepo/analysis_script.py" text="The Analysis" %}
