---
title: "Research"
permalink: /research/
---

You can view published articles and working papers on United Nations
peacekeeping from affiliated researchers below:

# Working papers

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}

# Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}