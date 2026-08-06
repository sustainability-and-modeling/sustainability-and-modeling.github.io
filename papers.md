---
layout: page
title: Accepted papers
permalink: /papers
order: 6
---

{% assign papers = site.data.papers %}

This year, we have accepted seven papers.

<div>
  <ul>
    {% for paper in papers %}
      <li><b>{{ paper.title }}</b><br/>by {{ paper.authors }}</li>
    {% endfor %}
  </ul>
</div>
