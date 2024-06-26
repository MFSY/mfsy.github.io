---
layout: page
title: Blue Brain Nexus
description: Blue Brain Nexus – Data and Knowledge Graph Management for Data-Driven Science
img: assets/img/nexus.png
importance: 1
category: work
category_about: selected
publications: [https://doi.org/10.3233/SW-222974]
---

---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div class="publications">
        {%- for h in page.publications %}
        {% bibliography -f papers -q @*[html={{h}}]* %}
        {% endfor %}

        </div>
    </div>
   <iframe width="50%" height=200 src="https://www.youtube.com/embed/8KkWpb_ZGmI?si=xTqG47mPxKQmOzO8" title="Thalamoreticular Microcircuitry Blue Brain Nexus Public Data Studio" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    <div class="caption">
    An open, secure, scalable data and Knowledge Graph management system built on open standards, interoperable semantic web technologies (RDF, JSON-LD, W3C SHACL) and based on streaming event-based architecture to support asynchronous building and maintenance of multiple extensible indices to ensure high performance search capabilities and enable analytics on ElasticSearch and a triple store.
    </div>
    
</div>
## Code 

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
    {% include repository/repo_covid19.html repository="BlueBrain/nexus" %}
</div>
{% endif %}
