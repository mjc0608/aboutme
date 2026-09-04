---
layout: default
title: Blog
---

<h3>Jiacheng's Blog</h3>
<ul>
{% for post in site.posts %}
<li><a href="{{ post.url }}">{{ post.title }}</a> &mdash; {{ post.date | date: "%Y-%m-%d" }}</li>
{% endfor %}
</ul>
