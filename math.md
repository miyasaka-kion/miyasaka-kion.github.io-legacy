---
layout: page
title: Mathematics
---

<section>
  <h1>{{ page.title }}</h1>

  <ul>
    {% for item in site.maths %}
        <li>
          <a href="{{ item.url }}">{{ item.title }}</a>
        </li>
    {% endfor %}
  </ul>
</section>