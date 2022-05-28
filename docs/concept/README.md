---
sort: 1
path: /concept
layout: concept
title: Our Concept
permalink: /concept
---

{%- for item in site.html_pages -%}
	{%- if item.path == 'docs/README.md' -%}
		{% include templates/anchor_headings.html html=item.content h_min=2 h_max=2 anchorBody="#" %}
	{%- endif -%}
{%- endfor -%}
