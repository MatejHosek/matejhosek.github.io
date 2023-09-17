---
title: "Notes"
layout: default
permalink: "/notes/"
---

# Poznámky
<div>
	{% for post in site.notes %}
		<ul class="list">
			<li><h3 class="list"><a class="list" href="{{ post.url }}">{{ post.title }}</a></h3></li>
		</ul>
	{% endfor %}
</div>
