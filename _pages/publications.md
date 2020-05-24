---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br>

<b>[Sixth-Order Accurate Schemes for Reinitialization and Extrapolation in
the Level Set Framework](https://tiankuizhang.github.io/publication/zhang2006sixth)</b><br>

<b>Tiankui Zhang</b> and Charles W Wolgemuth. Sixth-order accurate schemes for reinitialization and extrapolation in the level set framework.<i>Journal of Scientific Computing</i>, 83(2), 2020.

