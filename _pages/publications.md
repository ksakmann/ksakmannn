---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

Selected papers; for a complete list see my Google Scholar profile.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
