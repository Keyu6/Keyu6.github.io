---
layout: archive
title: "关于我"
permalink: /publications/
author_profile: true
---

More publications @ [DBLP](https://dblp.org/pid/205/0911.html)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
