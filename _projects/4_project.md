---
layout: page
title: Knowledge Graph Forge
description: A python framework for building, validating and using a knowledge graph
img: https://raw.githubusercontent.com/BlueBrain/nexus-forge/master/docs/source/assets/bbnforge
importance: 1
category: work
category_about: selected
publications: [https://doi.org/10.3233/SW-222974]
---

---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="https://raw.githubusercontent.com/BlueBrain/nexus-forge/master/docs/source/assets/bbnforge" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="caption">
    The Nexus Forge bring together json-based metadata transformations declarative rules, W3C SHACL validation, JSON-LD to build knowledge graphs from various sources, query them using SPARQL and ElasticSearch and perform entity linking using various query and ML based techniques.
    </div>
    
</div>

## [Documentation](https://nexus-forge.readthedocs.io)

## Code

{% highlight shell %}

pip install nexusforge

{% endhighlight %}

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
    {% include repository/repo.html repository="BlueBrain/nexus-forge" %}
</div>
{% endif %}


## Publication

<div class="publications">

{%- for h in page.publications %}
  {% bibliography -f papers -q @*[html={{h}}]* %}
{% endfor %}

</div>