---
layout: default
title: Все новости
---

## Все новости

<section class="archive_list">
  {% for post in site.posts %}

  <div class="post_title">
    <a href="{{ post.url }}">{{ post.title}}</a>
    <span class="date">{{ post.date | date: "%d.%m.%Y" }}</span>
  </div>

  {% endfor %}

</section>
