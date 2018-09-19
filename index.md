---
layout: home
permalink: /
title: "WeeMovies: a collection of 1 minute short movies"
tags: [Trans American Trail, Pan American Highway, Motorcycle adventure]
---

<div class="post-rows">

  <h2 class="section-title">BJJ</h2>

  {% for post in site.categories.bjj %}
    {% include post-list.html %}
  {% endfor %}

  <h2 class="section-title">Yoga</h2>

  {% for post in site.categories.yoga %}
    {% include post-list.html %}
  {% endfor %}

  <h2 class="section-title">Travel</h2>

  {% for post in site.categories.travel %}
    {% include post-list.html %}
  {% endfor %}

</div>
