---
layout: archive
title: "Misc"
permalink: /essays/
author_profile: true
---

{% include base_path %}

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
