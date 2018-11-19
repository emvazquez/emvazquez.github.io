---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

Education
======
 * Former student of École Normale Supérieure de Cachan
 * Professeur Agrégé
 * Ph.D. of Paris XI Orsay University
 * Habilitation à Diriger les Recherches

{% include base_path %}


<ul>{% for post in site.publications %}
{% include archive-single-cv.html %}
{% endfor %}</ul>
  
<ul>{% for post in site.talks %}
{% include archive-single-talk-cv.html %}
{% endfor %}</ul>
  
<ul>{% for post in site.teaching %}
{% include archive-single-cv.html %}
{% endfor %}</ul>
