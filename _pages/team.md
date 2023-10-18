---
permalink: /team/
title: "TEAM MEMBERS"
excerpt: "Our team"
---

**The team members at Synthetic Physiology Lab are made up of experienced and dedicated researchers from various disciplines and backgrounds. 
What unites them is an undying passion for learning and discovery. Meet them below.**
 
**We are always looking for talent: if you like what we are doing and think you can contribute, reach out.**

## Principal Investigator
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
      {% if post.tags contains "PI"%}
        {% include archive-single-team.html type="grid" %}
      {% endif%}
  {% endfor %}
</div>
</div>

## Senior scientists 
<div class="grid">
<div class="wrapper">
  {% for post in site.team reversed %}
      {% if post.tags contains "SeniorScientist"%}
        {% include archive-single-team.html type="grid" %}
      {% endif%}
  {% endfor %}
</div>
</div>

## Post-doctoral fellows
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
      {% if post.tags contains "Postdoc"%}
        {% include archive-single-team.html type="grid" %}
      {% endif%}
  {% endfor %}
</div>
</div>

## PhD students
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
      {% if post.tags contains "PhD"%}
        {% include archive-single-team.html type="grid" %}
      {% endif%}
  {% endfor %}
</div>
</div>
