---
layout: default
---

Le **Geneva Azure & PowerShell User Group** est destiné aux utilisateurs de la plateforme cloud Azure et du langage de scripting PowerShell, devenu incontournable dans les produits Microsoft. Quel que soit votre niveau, vous êtes les bienvenus pour assister aux présentations et échanger des conseils techniques ou des retours d’expérience.

## Nos prochains meetups

*En cours de préparation ...*

Retrouvez toutes les information sur le site [Meetup](https://www.meetup.com/fr-FR/Geneva-Azure-and-PowerShell-User-Group).

## Nos derniers articles

{% for post in site.posts limit:10 %}{% assign author = site.data.authors[post.author] %}
 - {{ post.date | date: "%-d %b, %Y" }} - [{{ post.title }}]({{ post.url }}) *par {{ author.name}}*{% endfor %}
