---
layout: page
title: Accepted papers
permalink: /papers
order: 6
---

{% assign papers = site.data.papers %}

This year, we only accepted one paper.

<div>
  <ul>
    {% for paper in papers %}
      <li><b>{{ paper.title }}</b><br/>by {{ paper.authors }}</li>
    {% endfor %}
  </ul>
</div>
