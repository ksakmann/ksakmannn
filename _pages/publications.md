---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

These are my favourite papers, for a complete list see  <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
