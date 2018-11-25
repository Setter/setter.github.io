---
layout: default.liquid
title: Home
---

### Posts

{% for post in collections.posts.pages %}

[{{ post.title }}]({{ post.permalink }})

{% endfor %}

