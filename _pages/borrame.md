 ---
layout: archive
title: "Expeditions"
permalink: /borrame/
author_profile: true
header:
  og_image: "images/gama_gama.png"
---

Here there are the funded expeditions in which I have been part of. Find photographs and brief explanations of the fieldwork purposes in each folder. Please, take into account that not all the photographs have been uploaded here, and you can see more directly on [iNaturalist](https://www.inaturalist.org/people/jimarcor).

<nbsp>

{% assign ordered_pages = site.borrame | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
