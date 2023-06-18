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


[Real-time Multi-person Eyeblink Detection in the Wild for Untrimmed Video](https://openaccess.thecvf.com/content/CVPR2023/papers/Zeng_Real-Time_Multi-Person_Eyeblink_Detection_in_the_Wild_for_Untrimmed_Video_CVPR_2023_paper.pdf)
Wenzheng Zeng, Yang Xiao, Sicheng Wei, Jinfang Gan, Xintao Zhang, Zhiguo Cao, Zhiwen Fang, Joey Tianyi Zhou
