---
title: Filmography
---

<h1>Filmography</h1>

<ul>
  {% for film in site.films %}
    <li>
      <h2><a href="{{ film.url }}">{{ film.title }}</a></h2>
      <h3>{{ film.credits }}</h3>
      <p>{{ film.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>
