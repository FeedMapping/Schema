---
sort: 1
path: /concept
layout: concept
permalink: /concept
title: Tabulate Prime by The Power of 168
---

{%- for item in site.html_pages -%}
	{%- if item.path == "docs/README.md" -%}
		{{ item.content }}
	{%- endif -%}
{%- endfor -%}
