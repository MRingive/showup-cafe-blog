---
layout: default-no-footer
title: Home
---

#### Blog

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

<br />

#### Working on

🙏 [Showing Up in Web3](https://www.theshowup.club/users/0x98Dce6Fc2b53Fa09A99061Ef10669A9Ae1F8DA34)

🤑 <a href="{{ site.url }}{% link financial-freedom-updates/index.md %}">Financial Freedom</a>

🎥 [A Video Series](https://www.youtube.com/channel/UCrBFVisOKEWPqgsKzNxDAqw)

<br />

#### Contact/Follow

👋 [Twitter](https://twitter.com/mat_tjo)

📽 [YouTube](https://www.youtube.com/channel/UCrBFVisOKEWPqgsKzNxDAqw)