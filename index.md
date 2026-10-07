---
layout: default
title: Home
---

# DjMondo Music

Straight-talk music platform focused on **Afrobeats**, African artists, industry trends, and real stories behind the sound.

---

## Latest Posts

<ul>
  {% for post in site.posts limit:10 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%b %-d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
