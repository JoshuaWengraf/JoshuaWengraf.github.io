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
* MPhys Physics (1st), <i>The University of Manchester</i>, 2013 - 2017
* MSc in Physics (by research) (Distinction), <i>Lancaster University</i>, 2018 - 2020

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
Research Projects
======
{% for post in site.research_experience reversed%}
  {% include archive-single.html %}
{% endfor %}

  
Public Engagement
======
  <ul>{% for post in site.public_engagement reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
Teaching
======
  <ul>{% for post in site.teaching reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Interests
======
  <ul>{% for post in site.interests reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
