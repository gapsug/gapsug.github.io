---
layout: page
title: Accueil
description: Bienvenue sur le site du Geneva Azure & Powershell User Group.
---

Le **Geneva Azure & PowerShell User Group** est destiné aux utilisateurs de la plateforme cloud Azure et du langage de scripting PowerShell, devenu incontournable dans les produits Microsoft. Quel que soit votre niveau, vous êtes les bienvenus pour assister aux présentations et échanger des conseils techniques ou des retours d’expérience.

Les sessions alternent entre des présentations Azure et PowerShell. Idéalement, nous allions les deux. Avec l’avènement du nouveau Microsoft, les partages ne sont pas limités à la plate-forme Windows. L’open source dans Azure, comme autour de PowerShell, a une place importante dans nos échanges. Comme Microsoft : “We love Linux!” (and MacOS).

## Nos membres

{% for member in site.data.members %}
 - **{{ member.role }}**: {{ member.name }}{% endfor %}