---
layout: default-no-footer
title: Home
---

<p>Welcome to the cafe ☕️</p>

<br />

#### Posts

<div>
{% for post in site.posts %}
  {% if post.hidden == False %}
    <p>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>{{ post.date | date: '%B %Y' }}</small>
    </p>
  {% endif %}
{% endfor %}
</div>