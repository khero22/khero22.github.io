---
layout: page
title: About
permalink: /about/
weight: 5
---

# **About Me**

Bonjour je suis **{{ site.author.name }}**,<br>
Architecte Gerant du Bureau d'Etude d'Architecture ACAD sis a Sidi Bel Abbes,
et passionné en développement informatique loisir que je pratique en temps libre avec la peinture.

<div class="row">
{% include about/skills.html title="Language de Programmation" source=site.data.programming-skills %}
{% include about/skills.html title="Logiciels d'Architecture" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>