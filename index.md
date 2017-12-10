---
layout: default
---

Bienvenue sur le site du Geneva Azure & PowerShell user group

## Nos articles

{% for post in site.posts %}

 - [{{ post.title }}]({{ post.url }})
 
{% endfor %}
