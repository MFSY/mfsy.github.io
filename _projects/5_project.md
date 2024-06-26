---
layout: page
title: BlueGraph
description: Unifying Python framework for graph analytics and co-occurrence analysis
img: https://raw.githubusercontent.com/BlueBrain/BlueGraph/master/examples/figures/BBP_Blue_Graph_banner.jpg
importance: 1
category: work
publications: [https://doi.org/10.3389/fpubh.2021.695139]
---

---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="https://raw.githubusercontent.com/BlueBrain/BlueGraph/master/examples/figures/BBP_Blue_Graph_banner.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="caption">
    BlueGraph is a Python framework that consolidates graph analytics capabilities from different graph processing backends. It provides a set of interfaces for co-occurrence graph generators and preprocessing as well as semantic property encoders; for graph analytics, graph metrics computing, path search and community detection; for representation learning API for applying various graph embedding techniques, representation learning downstream tasks API allowing the user to perform node classification, similarity queries, link prediction.
    </div>
    
</div>


## [Documentation](https://bluegraph.readthedocs.io)

## Code 

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
    {% include repository/repo_covid19.html repository="BlueBrain/BlueGraph" %}
</div>
{% endif %}

## Publication 

<div class="publications">

{%- for h in page.publications %}
  {% bibliography -f papers -q @*[html={{h}}]* %}
{% endfor %}

</div>
