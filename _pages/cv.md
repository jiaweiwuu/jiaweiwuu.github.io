---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD student, Rutgers University–New Brunswick
* B.Sc., School of Data Science and Engineering, East China Normal University

Research experience
======
* Research Assistant, Medical AI Lab, Westlake University  
  Mentor: Prof. Yefeng Zheng

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
