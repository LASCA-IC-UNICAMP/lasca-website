---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

TODO: add text about team

{% include section.html %}

# Faculty

{% include list.html data="members" component="portrait" filters="role: faculty" %}

{% include section.html background="images/background.jpg" dark=true %}

TODO: Add more text if we want

{% include section.html %}

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
