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

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

## Publications
{% include base_path %}

{% assign sorted = site.publications | reverse %}
{% for post in sorted %}
  {% include archive-single.html %}
{% endfor %}