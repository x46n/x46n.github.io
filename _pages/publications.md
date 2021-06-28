---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---
# Journal Papers
1. “Fulfilled by Amazon”: A Strategic Perspective of Competition at the E-commerce Platform, Major Revision at Manufacturing and Service Operations Management, joint work with Huihui Liu, Wenqiang Xiao and Guoming Lai.
2. Strategic Financing and Information Revelation Amid Market Competition, R&R at Management Science, joint work with Wenqiang Xiao and Guoming Lai.
3. Estimating Large-Scale Tree Logit Models via a Difference of Strictly Convex Functions, Major Revision at Operations Research, joint work with Srikanth Jagabathula and Paat Rusmevichientong.
4. The Coin of AI has Two Sides: Matching Enhancement and Information Revelation Effects of AI on Gig-Economy Platforms, Under Review at Management Science, joint work with Yi Liu, Bowen Lou, Xinxin Li.

# Conference Papers
1. Exploring Key Hackers and Cybersecurity Threats in Chinese Hacker Communities, 2016 IEEE Conference on Intelligence and Security Informatics (ISI), 13-18, joint work with Z Fang, Q Wei, G Chen, Y Zhang, C Xing, W Li and H Chen.




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
