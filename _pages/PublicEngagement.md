---
layout: archive
title: "Public Engagement"
permalink: /public_engagement/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.public_engagement reversed %}
  {% include archive-single.html %}
{% endfor %}
