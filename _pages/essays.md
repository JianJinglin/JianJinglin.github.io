---
layout: archive
title: "随记 / Essays"
permalink: /essays/
author_profile: true
---

{% include base_path %}

一些读书笔记、随想、和胡说八道。  
Some reading notes, reflections, and ramblings.

---

{% assign essays = site.posts | where: "category", "essays" %}
{% for post in essays %}
  <div style="margin-bottom: 2em;">
    <h2><a href="{{ post.url | prepend: base_path }}">{{ post.title }}</a></h2>
    <p style="color: #888; font-size: 0.9em;">{{ post.date | date: "%Y-%m-%d" }}</p>
    {{ post.excerpt }}
  </div>
{% endfor %}
