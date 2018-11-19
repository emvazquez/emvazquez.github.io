---
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find my publications on:
<ul>
<li> <a href="https://scholar.google.fr/citations?user=gyx2-dkAAAAJ">Google Scholar</a></li>
<li> <a href="https://cv.archives-ouvertes.fr/emmanuel-vazquez">CV-HAL</a></li>
</ul>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
