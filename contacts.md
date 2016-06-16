---
title: Contacts
layout: contacts
layout-source: https://github.com/hyip/hyip.github.io/blob/master/_layouts/contacts.html
permalink: /contacts
hyiplink: http://hyip.github.io/contacts
---
{% for repository in site.github.public_repositories %}						
- Name: [{{ repository.name }}]({{ repository.html_url }}) 
  {% if repository.fork %} (Forked){% endif %} - 
  Homepage: [<a href="{{ repository.homepage }}" target="_blank">{{ repository.homepage }}</a>]<br>
  {{ repository.description }} 
{% endfor %}					
