---
layout: archive

title: "Las recetas"
image:
  feature: feature_cocina_peruana_thin.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->