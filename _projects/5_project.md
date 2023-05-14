---
layout: page
title: Blue Brain Nexus
description: Blue Brain Nexus – Data Management for Data-Driven Science
img: assets/img/nexus.png
importance: 1
category: work
category_about: selected
publications: [https://doi.org/10.3233/SW-222974]
---

---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/nexus.png" title="example image" class="img-fluid rounded z-depth-1" max-height="400" max-width="400" width=400 %}
    </div>
    <div class="caption">
    An open, secure, scalable data and Knowledge Graph management system built on open standards, interoperable semantic web technologies (RDF, JSON-LD, W3C SHACL) and based on streaming event-based architecture to support asynchronous building and maintenance of multiple extensible indices to ensure high performance search capabilities and enable analytics on ElasticSearch and a triple store.
    </div>
</div>

## [Documentation](https://bluebrainnexus.io)

## Code 

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
    {% include repository/repo_covid19.html repository="BlueBrain/nexus" %}
</div>
{% endif %}

## Publication 

<div class="publications">

{%- for h in page.publications %}
  {% bibliography -f papers -q @*[html={{h}}]* %}
{% endfor %}

</div>