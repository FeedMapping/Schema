---
sort: 1
path: /concept
layout: concept
title: Our Concept
permalink: /concept
---

{%- for item in site.html_pages -%}
	{%- if item.path == 'docs/README.md' -%}
		{% assign nodes = item.content | split: '<h' %}
		{%- for node in nodes -%}
			{{ node }}
		{%- endfor -%}	
	{%- endif -%}
{%- endfor -%}
