---
layout: page
title: "Index"
permalink: "/index-hu/"
---

Index

<ul>
	{% for correction in site.index-hu %}
		<li>
			<a href="{{ correction.url }}">{{ correction.title }}</a>
			{{ correction.content }}
		</li>
	{% endfor %}
</ul>
