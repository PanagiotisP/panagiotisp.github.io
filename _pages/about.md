---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
# About Me

Hey! I'm Panagiotis, a third-year PhD student in the [GraphDeco](https://team.inria.fr/graphdeco/fr/) team, at INRIA and Université Côte D'Azur, supervised by [George Drettakis](https://www-sop.inria.fr/members/George.Drettakis/).
I'm fascinated by projects with a strong focus on speed and efficiency; achieving more without increasing the cost.
My research interests revolve around Gaussian Splatting, Scene Reconstruction and Relighting.

Before that, I spent 9 months in the [CVRL](https://www.ics.forth.gr/cvrl/) lab,
working as an R&D Engineer in [Panos Trahanias](https://www.ics.forth.gr/cvrl/person/Trahanias/Panos%20E.)'s team.
My biggest project was implementing a fluid-simulation program following [Robert Bridson's](https://www.cs.ubc.ca/~rbridson/) [book](https://www.taylorfrancis.com/books/mono/10.1201/9781315266008/fluid-simulation-computer-graphics-robert-bridson) in C++, using OpenVDB, and in Unreal Engine 5, using the particle system.

I completed my combined BSc/MSc at the School of Electrical and Computer Engineering in the [National Technical University of Athens](http://ece.ntua.gr/),
where I did my master's thesis under the supervision of professor [Petros Maragos](http://cvsp.cs.ntua.gr/maragos/).

Outside of work,
you can find me running, swimming and reading in the sunny beach of Nice.
Additionally, I have an ever-growing list of games to play and gifts to crochet...

I'm currently looking for internships for summer 2026.

## News
{% assign sorted = site.news | reverse %}
{% for news in sorted limit:4 %}
  {% include news.html %}
{% endfor %}

## Publications
{% include base_path %}

{% assign sorted = site.publications | reverse %}
{% assign count = sorted | size | minus: 2 %}
{% for post in sorted limit:count %}
  {% include archive-single.html %}
{% endfor %}