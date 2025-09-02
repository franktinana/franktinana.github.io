---
layout: page
title: Timeline
permalink: /timeline/
---
Below is a running log. Update `_data/timeline.yml` to add entries.
{% assign items = site.data.timeline | sort: 'date' %}
<ol>
{% for e in items %}
  <li><strong>{{ e.date }}</strong> — <em>{{ e.title }}</em><br>{{ e.summary }}</li>
{% endfor %}
</ol>
