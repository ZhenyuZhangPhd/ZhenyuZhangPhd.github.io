---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## Journal Papers ##
  1. ZhenyuZhang, et al, "AOA limited Scatterer Model for Next Generation Wireless Communication", subimitted to IEEE TVT.
  2. ZhenyuZhang, et al, "A Novel OTFS Target Detection Framework", subimitted to IEEE TWC.
  3. 还没有high quality research, 需要加油。
## Conference Papers ##
  1. 张振宇，基于机器学习的LOS/NLOS识别技术研究[D],2022，西南交通大学. You can find source code here: [Source code for Paper1](https://github.com/ZhenyuZhangPhd/SWJTU-Cover-Letter-Template)。
  2. 还没有发表会议论文，同时需加强presentation能力。

## Chinese Journal Papers ##
  1.算了，low quality papers不重要就不写了。
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
