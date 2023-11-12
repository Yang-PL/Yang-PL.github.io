---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

## Conference
* Simultaneous Radio and Physical Mapping
for Cellular-Connected UAV by Fusin
Radio and Sensing Data\
  **Yuhang Yang**, Xiaoli xu, Zeng Yong. [[ICC 2023]](..//files/a238-yang%20final.pdf)

## Journal
* Up to now, my journal paper is still being revised, so stay tuned.



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}







