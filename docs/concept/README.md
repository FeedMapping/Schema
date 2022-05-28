---
sort: 1
path: /concept
layout: concept
title: Our Concept
permalink: /concept
---

{%- for item in site.html_pages -%}
	{%- if item.path == 'docs/README.md' -%}
		{% capture item_content %}{{ item.content }}{% endcapture %}
		{% assign nodes = item_content | split: '<h' %}
		{{ nodes | size }}
	{%- endif -%}
{%- endfor -%}
