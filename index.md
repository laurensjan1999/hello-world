---
title: Laurens Jan
layout: default
---

<h1 class="headline">{{page.title}}</h1>
<div class="meta"><span>{{page.date | date: '%B %d, %Y'}}</span></div>
<div class="spacer"></div>
<h1>Posts</h1>
{% for post in site.posts %}
<h3><a href="{{post.url | prepend: site.baseurl}}">{{post.title}}</a></h3>
{% endfor %}
