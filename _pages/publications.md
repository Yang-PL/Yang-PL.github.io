---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  You can also find my articles on my [Google Scholar](https://scholar.google.com/citations?user=qIDX9aoAAAA).

## Conference
* [Simultaneous Radio and Physical Mapping
for Cellular-Connected UAV by Fusin
Radio and Sensing Data](..//files/a238-yang%20final.pdf)\
  **Yuhang Yang**, Xiaoli Xu, Zeng Yong*. ICC 2023

## Journal
* [Channel Knowledge Map for Cellular-Connected UAV via Binary Bayesian Filtering](https://arxiv.org/abs/2409.00016)\
  **Yuhang Yang**, Xiaoli Xu, Zeng Yong*, Haijian Sun and Rose Qingyang Hu. Submitted to IEEE Transactions on Communications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}







