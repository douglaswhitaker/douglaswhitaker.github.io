---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Selected publications; please see my CV for a complete list of publications.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
