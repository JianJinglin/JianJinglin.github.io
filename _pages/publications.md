---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## Intelligent Agents

Liu, H., Li, Y., **Jian, J.**, Cheng, Y., Lu, J., Guo, S., ... & Wang, H. (2024). Toward a Team of AI-made Scientists for Scientific Discovery from Gene Expression Data. <i>arXiv preprint arXiv:2402.12391. </i> Full text available at <a href="https://arxiv.org/abs/2402.12391"> </a>


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
