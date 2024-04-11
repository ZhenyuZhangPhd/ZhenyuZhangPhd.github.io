---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## Journal Papers ##
  1. 张振宇，基于机器学习的LOS/NLOS识别技术研究[D],2022，西南交通大学.

## Conference Papers ##
  1. 张振宇，基于机器学习的LOS/NLOS识别技术研究[D],2022，西南交通大学. You can find source code here: [Source code for Paper1](https://github.com/ZhenyuZhangPhd/SWJTU-Cover-Letter-Template)。

## Chinese Journal Papers ##
  1. 张振宇，基于随机森林的LOS/NLOS识别技术研究[D],2022，电讯技术.代码: [Source code](https://github.com/ZhenyuZhangPhd/SWJTU-Cover-Letter-Template)。
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
