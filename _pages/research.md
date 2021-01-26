---
title: "Research"
permalink: /research/
---

You can view working papers and published articles on United Nations
peacekeeping from affiliated researchers below.

# Working papers

{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}

# Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}