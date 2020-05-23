---
layout: archive
title: "Curriculum Vitae"
permalink: /CV/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* MPhys in Physics, 1st, <i>The University of Manchester University</i>, 2013 - 2017
* MSc in Physics (by research), Distinction, <i>Lancaster University</i>, 2018 - 2020

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Research Projects
======
<ul>{% for post in site.portfolio %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Public Engagement
======
  <ul>{% for post in site.publicEngagement %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Interests
======
<ul>{% for post in site.Interests %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

