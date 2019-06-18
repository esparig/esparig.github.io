---
layout: page
title: Projects
permalink: /projects/
---

Here I will update the information about my current projects...

{% for project in site.data.projects %}
  {% include project-outline.html project=project %}
{% endfor %}


