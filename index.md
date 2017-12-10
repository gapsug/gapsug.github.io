---
layout: default
---

## Nos prochains meetups

*En cours de préparation ...*

Retrouvez toutes les information sur le site [Meetup](https://www.meetup.com/fr-FR/Geneva-Azure-and-PowerShell-User-Group).

## Nos derniers articles

{% for post in paginator.posts %}
 - {{ post.date | date: "%-d %b, %Y" }} - [{{ post.title }}]({{ post.url }}) *par {{ post.author}}*{% endfor %}
