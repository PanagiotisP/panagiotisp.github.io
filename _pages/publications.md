---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% assign sorted = site.publications | reverse %}
{% assign count = sorted | size | minus: 2 %}
{% for post in sorted limit:count %}
  {% include archive-single.html %}
{% endfor %}
