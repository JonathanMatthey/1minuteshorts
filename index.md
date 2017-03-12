---
layout: home
permalink: /
title: "4 year adventure - stories and videos"
tags: [Trans American Trail, Pan American Highway, Motorcycle adventure]
image:
  feature: 4yadv-cover.jpg
---

<div class="tiles">
{% for post in site.categories.episodes %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
