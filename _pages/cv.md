---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
<br/><img src='/images/profile.jpg'>

Education
======
* Ph.D in Astronomy, HKU, 2025 (expected) - 
* M.S. in Astronomy, SYSU, 2022 - 2025
* B.S. in Physcis, SYSU, 2018 - 2022
  
Skills
======
* N-body simulations
* Python, Latex

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>


