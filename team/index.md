---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

# Faculty

{% include list.html data="members" component="portrait" filters="role: faculty" %}

# Post-docs

{% include list.html data="members" component="portrait" filters="role: postdoc" %}

# PhD candidates

{% include list.html data="members" component="portrait" filters="role: phd" %}

# MSc students

{% include list.html data="members" component="portrait" filters="role: msc" %}

# Undergraduate students

{% include list.html data="members" component="portrait" filters="role: bsc" %}


<!--
{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
-->
