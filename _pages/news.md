---
layout: page
permalink: /news/
title: news
description:
nav: true
nav_order: 6
---

{% assign sorted_news = site.news | sort: 'date' | 'reverse'%}

{% for news in sorted_news %}
  <h2>{{ news.title }}</h2>
  <p>{{ news.date | date: "%B %d, %Y" }}</p>
  {{ news.content }}
  <hr> <!-- Add a horizontal rule to separate the posts -->
{% endfor %}
