---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

### Research Pilosophy

My overall research goal is to understand complex hydrologic systems under complex stresses. My doctoral research focuses on karst hydrogeology, but I do not consider myself a karst hydrogeologist. Rather, I see myself as a hydro(geo)logist and karst as a complex hydrologic system (and oh boy is it!), and I hope to use this research as a way to learn how to tackle problems in context systems. 

My research interests extend into groundwater-surface water interactions, Critical Zone Science, aquatic geochemistry, hydrologic response to climate change and anthropogenic stresses, and environmental data science.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

# Replace Publications with Projects
## Can start a new _projects folder
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
