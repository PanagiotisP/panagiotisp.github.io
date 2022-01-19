---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Panagiotis and I aspire to entering a PhD program in the field of computer vision / machine learning.

I recently graduated from the School of Electrical and Computer Engineering in the [National Technical University of Athens](http://ece.ntua.gr/)
where I completed my master's thesis under the supervision of professor [Petros Maragos](http://cvsp.cs.ntua.gr/maragos/).

## News
{% assign sorted = site.news | reverse %}
{% for news in sorted %}
  {% include news.html %}
{% endfor %}

## Publications
{% include base_path %}

{% assign sorted = site.publications | reverse %}
{% for post in sorted %}
  {% include archive-single.html %}
{% endfor %}