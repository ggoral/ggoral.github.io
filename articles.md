---
layout: page
title: Articles
lang: en
---

In this section you will find the information you need of all articles

## Categories
{% for category in site.categories %}
<p>
  <a href="/categories#{{ category[0] | slugify }}">
    {{ category[0] | capitalize }}
  </a>
 ({{ category[1].size }})
</p>
{% endfor %}


## Articles
{% assign posts=site.posts | sort: 'date' %}
<ul>
{% for post in posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>
