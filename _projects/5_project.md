---
layout: page
title: Knowledge Graph and Graph Analytics for insights on COVID-19
description: knowledge graph generation, analysis and exploration from COVID-19 Open Research Dataset to perform literature review of the role of glucose metabolism deregulations in the progression of COVID-19.
img: https://www.frontiersin.org/files/Articles/695139/fpubh-09-695139-HTML-r1/image_m/fpubh-09-695139-g001.jpg
importance: 1
category: work
category_about: selected
publications: [https://doi.org/10.3389/fpubh.2021.695139]
---

---



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="https://www.frontiersin.org/files/Articles/695139/fpubh-09-695139-HTML-r1/image_m/fpubh-09-695139-g001.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="caption">
    Knowledge Graph building and analytics pipeline from scientific literature (using NLP) to graph analytics. I enjoyed working on entity linking to build a co-occurence knowledge graph from extracted entities and on graph analytics to derive insights.
    </div>
    
</div>

## Code 

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
    {% include repository/repo_covid19.html repository="BlueBrain/BlueGraph/tree/master/cord19kg" %}
</div>
{% endif %}

## Publication 

<div class="publications">

{%- for h in page.publications %}
  {% bibliography -f papers -q @*[html={{h}}]* %}
{% endfor %}

</div>
