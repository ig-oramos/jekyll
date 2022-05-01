---
layout: home
title: Home
---
<h2>Posts:</h2>
{% for post in site.posts %}
<p><a href="{{post.url | relative_url }}">{{post.title}}</a></p>
{% endfor %}