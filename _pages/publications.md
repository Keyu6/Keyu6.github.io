---
layout: archive
title: "刘克宇"
permalink: /publications/
author_profile: true
---

关于我
======
我目前是西南交通大学计算机与人工智能学院的四年级博士研究生。主要的研究方向为粒计算，数据挖掘，机器学习。

论文成果
======
论文成果信息可参见：[DBLP](https://dblp.org/pid/205/0911.html)。

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
