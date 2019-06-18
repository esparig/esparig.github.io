---
layout: page
title: Projects
permalink: /projects/
---

{% for project in site.projects.projects %}
  {% include project-outline.html project=project %}
{% endfor %}


