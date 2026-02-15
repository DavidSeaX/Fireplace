---
title: Journal
layout: collection
permalink: /journal/
#collection: journal
---

{% assign sorted = site.journal | sort: 'date' | reverse %}

{% for post in sorted %}
  {% include archive-single.html %}
{% endfor %}