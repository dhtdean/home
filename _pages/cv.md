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
* Ph.D in Materials Science & Engineering, Stanford University, 2022
* M.S. in Computational & Mathematical Engineering, Stanford University, 2020


Work experience
======
* 2024/10 - Present: AGI strategy expert
  * ByteDance

* 2022/01 - 2024/09: Associate
  * McKinsey

* 2016/09 - 2022/01: Research Assistant
  * Stanford University

  
Skills
======
* Business strategy
* Finance
* Scientific computing & AI
* Coding

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
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  