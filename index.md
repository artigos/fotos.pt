---
layout: index
title: Fotos.pt
overview: true
---

<span class="latest-article">Últimos artigos sobre fotografia</span>

<ul class="index" markdown="0">
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> <span class="date">{{ post.date | date: "%-d/%m/%Y" }}</span></li>
  {% endfor %}
</ul>
