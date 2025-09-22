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

In addition, we have accepted one flash talk.

<li><b>Ethical and Sustainable AI? Lessons from Participatory Modeling</b><br/>by Laura Schmitt Olabisi, Jennifer Helgeson, and Rebecca Jordan</li>
