---
layout: page
title: "Origo"
permalink: "/origo/"
---

Origo

<ul>
	{% for correction in site.origo %}
		<li class="correction">
			<a href="{{ correction.url }}">{{ correction.title }}</a>
			{{ correction.content }}
		</li>
	{% endfor %}
</ul>
