---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## Journal Papers ##
  1. Z. Zhang, Q. Wang, G. Liu, F. Gao, and P. Fan, “Cross-Frame OTFS Parameter Estimation Based On Chinese Remainder Theorem,” IEEE Transactions on Wireless Communications, pp. 1–1, 2025, doi: 10.1109/TWC.2025.3596965.
  2. Z. Zhang and P. Deng, “An AOA Limited Scattering Model and Its Statistics in Next Generation Wireless Communications,” IEEE Trans. Veh. Technol., vol. 74, no. 3, pp. 5130–5134, Mar. 2025, doi: 10.1109/TVT.2024.3492232.
  3. Submitted to TWC, et al.
## Conference Papers ##
  1. Submitted to ICC, et al.

## Patents ##
  1. 还没有
## Chinese Journal Papers ##
  1. 算了，low quality papers不重要就不写了。
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
