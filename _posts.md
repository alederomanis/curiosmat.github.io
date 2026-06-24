---
layout: page
title: Articoli
---
<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.date | date: "%d %B %Y" }}</p>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
