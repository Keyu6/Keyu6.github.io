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
论文成果信息请参见：[DBLP](https://dblp.org/pid/205/0911.html)。

教育经历
======
2013-2017 江苏科技大学

2017-2020 江苏科技大学

2020-     西南交通大学

荣誉奖励
======
国奖奖学金

江苏省优秀学术学位硕士学位论文

西南交通大学博士生扬华新秀奖学金

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
