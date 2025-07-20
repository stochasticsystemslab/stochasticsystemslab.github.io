---
layout: default
title: Research
---

# Research Areas

{% for area in site.data.research.research %}
## {{ area.area }}

**Topics:**
<ul>
  {% for topic in area.topics %}
    <li>{{ topic }}</li>
  {% endfor %}
</ul>

**Support:**
<ul>
  {% for grant in area.support %}
    <li>{{ grant }}</li>
  {% endfor %}
</ul>
{% endfor %}
