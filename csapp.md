---
layout: page
title: Computer System A Programmer's Prospective
---

<section>
<h1>{{ page.title }}</h1>
<ul>
{% for post in site.maths %}
  {% if post.categories contains 'csapp' %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endif %}
{% endfor %}
</ul>
</section>