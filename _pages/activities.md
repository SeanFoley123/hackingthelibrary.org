---
layout: page
title: Class Notes
---

{% for day in site.days reversed %}
[{{day.title}} – {{day.class_date | date: '%A, %-d %B'}}]({{day.url}})
: {{day.description}}
{% endfor %}
