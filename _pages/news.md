---
layout: archive
title: "News"
permalink: /news/
---

{% include base_path %}

{% for post in site.news reversed %}
  {% include archive-single.html %}
{% endfor %}
