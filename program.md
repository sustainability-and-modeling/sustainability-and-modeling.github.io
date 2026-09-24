---
layout: page
title: Program
permalink: /program
order: 2
---

{% assign papers = site.data.papers %}

<h1>Program</h1>

<h3>Session: AM1</h3>

<ul>
    <li>09:15-09:30&nbsp;&nbsp;Opening</li>
    <li>09:30-09:50&nbsp;&nbsp;{% assign paper = papers | where: "id", 8 | first %}<strong>{{ paper.title }}</strong><br>{{ paper.authors }}</li>
    <li>09:50-10:10&nbsp;&nbsp;{% assign paper = papers | where: "id", 4 | first %}<strong>{{ paper.title }}</strong><br>{{ paper.authors }}</li>
    <li>10:10-10:30&nbsp;&nbsp;{% assign paper = papers | where: "id", 7 | first %}<strong>{{ paper.title }}</strong><br>{{ paper.authors }}</li>
</ul>

10:10-10:30&nbsp;&nbsp;Break

<h3>Session: AM2</h3>

<ul>
    <li>11:00-11:20&nbsp;&nbsp;{% assign paper = papers | where: "id", 5 | first %}<strong>{{ paper.title }}</strong><br>{{ paper.authors }}</li>
    <li>11:20-11:40&nbsp;&nbsp;{% assign paper = papers | where: "id", 3 | first %}<strong>{{ paper.title }}</strong><br>{{ paper.authors }}</li>
    <li>11:40-12:00&nbsp;&nbsp;{% assign paper = papers | where: "id", 1 | first %}<strong>{{ paper.title }}</strong><br>{{ paper.authors }}</li>
    <li>12:00-12:20&nbsp;&nbsp;{% assign paper = papers | where: "id", 2 | first %}<strong>{{ paper.title }}</strong><br>{{ paper.authors }}</li>
    <li>12:20-12:40&nbsp;&nbsp;{% assign paper = papers | where: "id", 6 | first %}<strong>{{ paper.title }}</strong><br>{{ paper.authors }}</li>
    <li>12:40-13:00&nbsp;&nbsp;Concluding remarks</li>
</ul>

10:10-10:30&nbsp;&nbsp;Lunch

<h3>Session: PM</h3>

TBA
