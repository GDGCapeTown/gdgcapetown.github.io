---
layout: page
title:
tagline: Projects
---
{% include JB/setup %}

![GDG Cape Town]({{ site.url }}/assets/GDG_CapeTown.jpg)

##Google Cloud Platform Events

## Android Events

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## The Group

