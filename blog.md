---
layout: default.liquid
title: OBS Blog
---

# Posts

<ol id="posts-listing">
{% for post in collections.posts.pages limit:15 %}
<li>
<article>
	<h3><a href="{{post.permalink}}">{{post.title}}</a>
</article>
</li>
{% endfor %}
</ol>
