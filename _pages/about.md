---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Panagiotis and I aspire to work in the AR/VR area as a researcher/R&D engineer. I am currently working as an R&D engineer at the CVRL, FORTH, while actively seeking for a PhD position.

I graduated from the School of Electrical and Computer Engineering in the [National Technical University of Athens](http://ece.ntua.gr/)
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