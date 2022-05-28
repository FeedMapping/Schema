---
sort: 1
path: /concept
layout: concept
title: Our Concept
permalink: /concept
---

{%- for item in site.html_pages -%}
	{%- if item.path == "docs/README.md" -%}
		{{ item.content }}
	{%- endif -%}
{%- endfor -%}
