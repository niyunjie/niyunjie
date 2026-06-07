---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Current
======

* Building and maintaining this personal website.
* Strengthening fundamentals in automation, engineering, mathematics, and programming.
* Learning and practicing MATLAB.
* Exploring possible research directions.

Planned
======

* Add selected course projects and experiments.
* Add small MATLAB simulations or engineering practice notes.
* Update this page when projects become more concrete.

{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}
