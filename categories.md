---
layout: page
title: "Categories"
permalink: /categories
---

{% for category in site.categories %}
  {% capture category_name %}{{ category | first }}{% endcapture %}

  <h3 id="{{ category_name | slugify }}">{{ category_name | capitalize }}</h3>
  <ul>
    {% for post in site.categories[category_name] %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <small>{{ post.date | date: "%Y-%m-%d" }}</small>
      </li>
    {% endfor %}
  </ul>
{% endfor %}