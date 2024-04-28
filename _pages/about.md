---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
# About Me

I am a first-year PhD student in the [GraphDeco](https://team.inria.fr/graphdeco/fr/) team, at INRIA and Université Côte D'Azur, supervised by [George Drettakis](https://www-sop.inria.fr/members/George.Drettakis/).

Before that, I spent 9 months in the [CVRL](https://www.ics.forth.gr/cvrl/) lab,
working as an R&D Engineer in various european-funded projects,
in [Panos Trahanias](https://www.ics.forth.gr/cvrl/person/Trahanias/Panos%20E.)'s team.

I completed my combined BSc/MSc at the School of Electrical and Computer Engineering in the [National Technical University of Athens](http://ece.ntua.gr/),
where I did my master's thesis under the supervision of professor [Petros Maragos](http://cvsp.cs.ntua.gr/maragos/).

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