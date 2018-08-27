---
layout: page
title: "Magyar Idok"
permalink: "/magyar-idok/"
---

Magyar Idok

<ul>
	{% for correction in site.magyar-idok %}
		<li>
			<a href="{{ correction.url }}">{{ correction.title }}</a>
			{{ correction.content }}
		</li>
	{% endfor %}
</ul>
