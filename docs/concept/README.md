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
		{% include templates/anchor_headings.html html=item_content anchorBody="#" %}
	{%- endif -%}
{%- endfor -%}
