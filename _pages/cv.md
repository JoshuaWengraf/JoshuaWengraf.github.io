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
* MPhys in Physics, The University of Manchester University, 2013 - 2017
* MSc in Physics (by research),  Lancaster University, 2017-2020

Research experience
======
<ul>{% for post in site.ResearchExperience %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  Public Engagement
======
  <ul>{% for post in site.PublicEngagement %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
