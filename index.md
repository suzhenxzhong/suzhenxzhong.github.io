---
permalink: /
title: "Suzhen Zhong"
layout: single
author_profile: true
---

# About Me
Suzhen Zhong is a researcher in **Software Engineering & AI** at Queen’s University, Canada.  
Her focus includes developer–LLM collaboration, agentic software processes, and empirical SE.

# Publications
For the most up-to-date list of my publications, please see my [Google Scholar page](https://scholar.google.com/citations?user=<your_id>).

{% include base_path %}

{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single-cv.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
{% endif %}