---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

LASCA

Av. Albert Einstein, 1251, Room 84

Cidade Universitária Zeferino Vaz

13083-852 Campinas SP Brazil


{%
  include button.html
  type="email"
  text="hilder@unicamp.br"
  link="hilder@unicam.br"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps?ll=-22.814837,-47.064771&z=15&t=m&hl=pt-BR&gl=US&mapclient=embed&cid=15164044859514240368"
%}

{% include section.html dark=true %}

{% capture col1 %}
TODO: add some text?
{% endcapture %}

{% capture col2 %}
TODO: add some text?
{% endcapture %}

{% capture col3 %}
TODO: add some text?
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
